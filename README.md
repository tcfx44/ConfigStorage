## ESP_ConfigStore
ESP_ConfigStore is a library for the ESP32/ESP8266 Arduino platform to store configuration parameters in the file system.

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/Tost69/ESP_ConfigStore/blob/master/LICENSE)

---
---

## Table of Contents

* [Changelog](changelog.md)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
  * [Use Arduino Library Manager](#use-arduino-library-manager)
  * [Manual Install](#manual-install)
  * [VS Code & PlatformIO](#vs-code--platformio)
* [HOWTO Usage](#howto-usage)
* [Examples](#examples)
  * [ 1. ConfigStore_ESP32](examples/ConfigStore_ESP32)
  * [ 2. ConfigStore_ESP8266](examples/ConfigStore_ESP8266)
* [Debug](#debug)
* [Troubleshooting](#troubleshooting)
* [Issues](#issues)
* [TO DO](#to-do)
* [DONE](#done)
* [License](#license)
* [Copyright](#copyright)

---
---

## Prerequisites

1. [`Arduino IDE 1.8.19+` for Arduino](https://github.com/arduino/Arduino). [![GitHub release](https://img.shields.io/github/release/arduino/Arduino.svg)](https://github.com/arduino/Arduino/releases/latest)
2. [`ESP32 Core 2.0.2+`](https://github.com/espressif/arduino-esp32) for ESP32-based boards. [![Latest release](https://img.shields.io/github/release/espressif/arduino-esp32.svg)](https://github.com/espressif/arduino-esp32/releases/latest/)
3. [`ESP8266 Core 3.0.2+`](https://github.com/esp8266/Arduino) for ESP8266-based boards. [![Latest release](https://img.shields.io/github/release/esp8266/Arduino.svg)](https://github.com/esp8266/Arduino/releases/latest/). SPIFFS is deprecated from ESP8266 core 2.7.1+, to use LittleFS. 

4. [`LittleFS_esp32 v1.0.6+`](https://github.com/lorol/LITTLEFS) for ESP32-based boards using LittleFS with ESP32 core v1.0.5-. To install, check [![arduino-library-badge](https://www.ardu-badge.com/badge/LittleFS_esp32.svg?)](https://www.ardu-badge.com/LittleFS_esp32). **Notice**: This [`LittleFS_esp32 library`](https://github.com/lorol/LITTLEFS) has been integrated to Arduino [ESP32 core v1.0.6+](https://github.com/espressif/arduino-esp32/tree/master/libraries/LITTLEFS) and you don't need to install it if using ESP32 core v1.0.6+

---
---

## Installation

### Use Arduino Library Manager
The best and easiest way is to use `Arduino Library Manager`. Search for `ESP_ConfigStore`, then select / install the latest version. You can also use this link [![arduino-library-badge](https://www.ardu-badge.com/badge/ESP_ConfigStore.svg?)](https://www.ardu-badge.com/ESP_ConfigStore) for more detailed instructions.

### Manual Install

1. Navigate to [ESP_ConfigStore](https://github.com/Tost69/ESP_ConfigStore) page.
2. Download the latest release `ESP_ConfigStore-master.zip`.
3. Extract the zip file to `ESP_ConfigStore-master` directory 
4. Copy the whole `ESP_ConfigStore-master` folder to Arduino libraries' directory such as `~/Arduino/libraries/`.

### VS Code & PlatformIO:

1. Install [VS Code](https://code.visualstudio.com/)
2. Install [PlatformIO](https://platformio.org/platformio-ide)
3. Install [**ESP_ConfigStore** library](https://registry.platformio.org/libraries/tost69/ESP_ConfigStore) by using [Library Manager](https://registry.platformio.org/libraries/tost69/ESP_ConfigStore/installation). Search for **ESP_ConfigStore** in [Platform.io Author's Libraries](https://platformio.org/lib/search?query=author:%22Tost69%22)
4. Use included [platformio.ini](platformio/platformio.ini) file from examples to ensure that all dependent libraries will installed automatically. Please visit documentation for the other options and examples at [Project Configuration File](https://docs.platformio.org/page/projectconf.html)

---
---
