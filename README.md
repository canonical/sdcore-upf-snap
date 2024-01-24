# SD-Core User Plane Function (UPF) Snap

A snap for the SD-Core User Plane Function

## Usage

### Install

```bash
sudo snap install sdcore-upf
```

### Configure

Configure the upf bessd by editing the `/var/snap/sdcore-upf/common/upf.json` file.

### Start

Start the services:

```bash
sudo snap start sdcore-upf.bessd
sudo snap start sdcore-upf.routectl
```

### Observe

Read the logs:

```bash
journalctl -b --no-pager -u snap.sdcore-upf.bessd.service -f
journalctl -b --no-pager -u snap.sdcore-upf.routectl.service -f
```
