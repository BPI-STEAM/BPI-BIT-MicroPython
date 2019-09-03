
# &emsp;&emsp;&emsp;&emsp;&emsp;BPI-BIT MicroPython 发布页

[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)
![](https://img.shields.io/github/release/BPI-STEAM/BPI-BIT-MicroPython.svg)
![](https://img.shields.io/github/license/BPI-STEAM/BPI-BIT-MicroPython.svg)
![](https://img.shields.io/badge/support-esp%20idf-red.svg)
![](https://img.shields.io/badge/support-smartconfig-FF00FF.svg)
![](https://img.shields.io/badge/custom-firmware-0AAAAF.svg)

## 烧写教程

[刷入 MicroPython 固件](https://bpi-steam-docs.readthedocs.io/zh_CN/latest/micropython/tutorials/flash_mpy.html)

## 相关教程

[Python3 菜鸡教程](https://www.runoob.com/python3/python3-tutorial.html)

[BPI-BIT 基础文档](https://bpi-steam-docs.readthedocs.io/zh_CN/latest/micropython/tutorials/index.html)

## 提供 SDK 示例

[MicroPython-Samples](https://github.com/BPI-STEAM/MicroPython-Samples)

## 相关软件

[点此查看软件正式发布页，获取软件吧](release.md)

| 其他软件 | 软件备注                            |
| :----------------------------------------------------------: | ------------------------------------------------------------ |
| [intellij-MicroPython](https://github.com/BPI-STEAM/BPI-BIT-MicroPython/releases/tag/pycharm) | 用于 Pycharm Mpfshell 的插件，还未并入官方主仓。             |
| [firmware release](https://github.com/BPI-STEAM/BPI-BIT-MicroPython/releases) | 和 MicroPython 有关的固件或工具会在此更新存放             |
| [vscoe-mpfshell](https://github.com/junhuanchen/vscode-mpfshell) | 用于 VsCode Mpfshell 的插件，可在 VSCODE 中直接得到。        |
| [EspTouch](https://github.com/EspressifApp/EspRelease/tree/master/EspTouch) | 用于 esp32 的 Smartconfig 辅助 WIFI 配网 APK 软件            |
|   [MobaxTerm](https://mobaxterm.mobatek.net/download.html)   | 免费绿色版的超级终端，支持大量远端连接，常用 Serial 和 FTP。 |
| [BleTool](https://github.com/BPI-STEAM/BPI-BIT-MicroPython/releases/tag/BleTool) | 提供 MicroPython 蓝牙示例代码 和 安卓主机蓝牙调试工具。      |

## 固件源码

[BPI-STEAM/micropython](https://github.com/BPI-STEAM/micropython)

## [更新日志](https://github.com/BPI-STEAM/BPI-BIT-MicroPython/releases)

### 20190623 添加软串口

- 本次更新没有礼品。
- 添加了软串口模块，代码在 [serial.py](https://github.com/BPI-STEAM/MicroPython-Samples/blob/master/02.inputs/serial.py) 。
- 你可以不再担心串口数量了，但注意，只有 9600 最稳定，57600 会抖动，115200 待修复（IDF 下正常）。

### 20190621 同步主仓更新

- 本次更新有礼品。
- 除了上次的 machine.I2S、bluetooth、smartconfig等功能，这次还加了 machine.SDcard 。
- 修复了一些不重要的性能问题，Python 的执行速度有提升。

### 20190528 第一个版本

- 网络层各种加持，mdns、smartconfig、XSocket、Mqtt 等等内置。
- 兼任 microbit 接口函数。
- 内置了一些常用模块代码。
