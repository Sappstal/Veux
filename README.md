# Device tree for Poco/Pocophone F1 (codenamed _"beryllium"_)

==================================

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Qualcomm SDM845 Snapdragon 845
CPU     | Octa-core (4x2.8 GHz Kryo 385 Gold & 4x1.8 GHz Kryo 385 Silver)
GPU     | Adreno 630
Memory  | 6 GB RAM
Shipped Android Version | 8.1 with MIUI 9.5
Storage | 64/128/256 GB
Battery | Non-removable Li-Ion 3400 mAh battery
Display | 1080 x 2246 pixels, IPS LCD, 18.7:9 ratio (~403 ppi density)
Camera  | 12 MP, f/1.9, 1/2.55", 1.4µm, dual pixel PDAF, 5 MP, f/2.0, (depth)

## Device picture

![Xiaomi POCO F1](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-pocophone-f1-2.jpg)

## Building
Generally, see https://wiki.orangefox.tech/en/dev/building

### Variants
1. For standard mode, build without any additional flags.
2. To build for ROMs using retrofitted dynamic partitions, run "export FOX_USE_DYNAMIC_PARTITIONS=1" before building.
3. To build for ROMs using borrowed keymaster 4.0, run "export FOX_USE_KEYMASTER_4=1" before building.

## Copyright
 ```
  /*
  *  Copyright (C) 2018 The LineageOS Project
  *
  *  Copyright (C) 2019-2023 The OrangeFox Recovery Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
