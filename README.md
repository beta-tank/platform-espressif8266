# Forked base repo and just target https://github.com/esp8266/Arduino.git#2.5.0-beta2
# In this release PEAP works fine
# Discussion:  https://github.com/esp8266/Arduino/issues/3442

# Espressif 8266: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-espressif8266.svg?branch=develop)](https://travis-ci.org/platformio/platform-espressif8266)
[![Build status](https://ci.appveyor.com/api/projects/status/aob49qatio84iygj/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-espressif8266/branch/develop)

Espressif Systems is a privately held fabless semiconductor company. They provide wireless communications and Wi-Fi chips which are widely used in mobile devices and the Internet of Things applications.

* [Home](http://platformio.org/platforms/espressif8266) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/espressif8266.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = espressif8266
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-espressif8266.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/espressif8266.html).
