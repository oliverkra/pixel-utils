### Links

https://launchpad.net/~longsleep/+archive/ubuntu/pixel-extras/+packages

### Required packages

- https://launchpad.net/~longsleep/+archive/ubuntu/pixel-extras/+files/ectool_1.7.0-1_amd64.deb

### Install scripts

```
sudo cp pixel-ectool /usr/local/bin/pixel-ectool
sudo chown root: /usr/local/bin/pixel-ectool
sudo chmod 0777 /usr/local/bin/pixel-ectool
```

### Examples

- Control fan speed
  - Set fan speed to a percentage ```pixel-ectool fanduty <percentage>```
  - Get fan RPM ```pixel-ectool pwmgetfanrpm```
  - Restore fan to auto control ```pixel-ectool autofanctrl on```

- Control keyboard backlight
  - Get backlight percentage ```pixel-ectool pwmgetkblight```
  - Set backlight percentage ```pixel-ectool pwmsetkblight <percentage>```