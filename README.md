# SD-Core User Plane Function (UPF) Snap

A snap for the SD-Core User Plane Function.

### Usage

Configure the UPF by editing the `/var/snap/sdcore-upf/common/upf.json` file, then start the individual services:
* `sudo snap start sdcore-upf.routectl`
* `sudo snap start sdcore-upf.bessd`
* `sudo snap start sdcore-upf.pfcpiface`

## Reference

- [SD-Core](https://opennetworking.org/sd-core/)
