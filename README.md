
## lastrain - weewx extension that provides extended statistics for reports
Copyright 2015-2023 Vince Skahan

This search list extension offers extra tags:

  * 'last_rain':            datetime of the last rain recorded in the database
  * 'time_since_last_rain': time (seconds) since the last rain was recorded

An example minimal skin is provided to show usage for including last rain data in your skin(s).

### VERSION COMPATIBILITY NOTE
This branch is compatible with WeeWX version 5  and later.

### Installation instructions:
This extension can be installed/uninstalled using the WeeWX extension installer.

#### 1. install the extension with the WeeWX extension installer

For weewx 5.x:

`weectl extension install https://github.com/weewx-contrib/lastrain-extension`

#### 2. restart weewx

`sudo systemctl restart weewx`

