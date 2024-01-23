# SD-Core User Plane Function (UPF) Snap

A snap for the SD-Core User Plane Function

## Usage

Install the snap:

```bash
sudo snap install sdcore-upf
```

Configure the upf by editing the `/var/snap/sdcore-upf/common/upf.json` file.

Start the bessd service:

```bash
sudo snap start sdcore-upf.bessd
```

Read the logs:

```bash
journalctl -b --no-pager -u snap.sdcore-upf.bessd.service -f
```
