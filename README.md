# hass-evnotify
Home Assistant component for EVNotify (supporting HACS)

## Install

 - Install via HACS (add this as a custom repository)
 - Get akey and password from evnotify
 - Add something like this to `configuration.yaml`
```
- platform: evnotify
  akey: 126gef
  password: !secret evnotify_pass
  scan_interval: 300
```
 - Restart HA
