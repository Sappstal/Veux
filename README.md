# Device tree for Redmi Note 11 Pro 5G (codenamed _"veux"_)

==================================

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Qualcomm SM6375 Snapdragon 695G (6 nm)
CPU     | Octa-core (2x2.2 GHz Kryo 660 Gold & 6x1.7 GHz Kryo 660 Silver)
GPU     | Adreno 619
Memory  | 6 GB / 8 GB
Shipped Android Version | Android 13, MIUI 14
Storage | 64/128/256 GB
Battery | Non-removable Li-Ion 5000 mAh battery
Display | 6.67 inches, 107.4 cm2 (~86.0% screen-to-body ratio)
Wide Camera  | 108 MP, f/1.9, 26mm (wide), 1/1.52", 0.7µm, PDAF
Ultrawide Camera	 | 8 MP, f/2.2, 118˚ (ultrawide)
Macro Camera	 | 2 MP, f/2.4, (macro)
Front Camera | 	16 MP, f/2.5, (wide), 1/3.06" 1.0µm





## Device picture

![Redmi Note 11 Pro 5G](https://github.com/Sappstal/Veux/assets/88688508/1d02bb14-e3b1-475a-b0ad-5de5ec8abea4)

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
