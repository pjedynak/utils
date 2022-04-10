# Monitor Hotplug
This script is prepared for auto-switching between plugged/unplugged monitors.

## Installation
1. copy *monitor_hotplug* to /usr/local/bin/
2. copy *80-monitor_hotplug.rules* to /etc/udev/rules.d/
3. invoke `udevadm control --reload-rules`
4. that's it

## TODO
* disable externals monitor when unplugged
* create support for configuration
* connect with *Awesome WM*

