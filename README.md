# End-World-Kit
末世生存装置——帮助你在废土世界中(比如核战争后的世界)更好地生存的传感器平台

## 安装的传感器

| 型号 | 描述 |
| ----- | ----------- |
| BMP280 | 温度、气压(可据此推算海拔) |
| SHT30D | 温度与湿度 |
| BH1750 | 数字光强度 |
| CCS811 | 二氧化碳与挥发性有机物 |
| MPU6050 | 6轴加速度与倾角传感器(附带温度) |
| S12SD | 紫外线强度 |
| [Open-Radiation-Detector](https://hackaday.io/project/27508-open-radiation-detector) | 辐射检测 |
| ATGM336H | 北斗+GPS双模定位模组(**未安装测试**) |

## 工程组织

原理图&PCB使用Kicad 5.1.9设计，4层板
软件使用Visual GDB+Arduino框架为ESP32开发，使用了很多第三方库

# English README

End World-Kit --- A sensor platform which makes your living more easier in the Wastland world (eg: a world after nuclear war)

## Sensors on board:

| Model | Description |
| ----- | ----------- |
| BMP280 | Temperature and Pressure (and altitude)|
| SHT30D | Temperature and Humidity |
| BH1750 | Digital Light (lux) |
| CCS811 | CO2 and TVOC |
| MPU6050 | 6-axis Gyro (and Temperature) |
| S12SD | UV Light Level |
| [Open-Radiation-Detector](https://hackaday.io/project/27508-open-radiation-detector) | Radiation Detect |
| ATGM336H | BD+GPS (**Not Tested yet**) |

## Project Structure

Schematic & PCB were designed using Kicad 5.1.9, 4-Layer PCB.

ESP32 was deved using Visual GDB & Arduino Framework, lots of 3rd-party libraries were used.