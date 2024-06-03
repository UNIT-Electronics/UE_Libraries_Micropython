# UE_Libraries_Micropython

The libraries published here focus on development in MicroPython, offering updated versions of various programs. These programs are available on the free PyPI platform, ensuring easy implementation.

## Loadupch

Loadupch is a software designed to work in the Windows environment for easy use, requiring no advanced installation. It runs on Python 3.9 and is based on code from [Stefan Wagner](https://github.com/wagiminator). The software provides a Tkinter interface for uploading firmware (.bin files) to the CH552 microcontroller with bootloader 2.40. The code is based on [chprog.py](https://github.com/wagiminator/CH552-USB-NRF/blob/main/software/nrf2cdc/tools/chprog.py).

<div align="center">

| Library  | Version | Link                                      |
|----------|---------|-------------------------------------------|
| loadupch | 0.0.3   | [https://pypi.org/project/loadupch/](https://pypi.org/project/loadupch/) |

</div>

> [!CAUTION]  
> This version has only been tested for loading firmware and may contain bugs.

## Ocks

This library features a modified version of the [micropython-ssd1306 library](https://github.com/stlehmann/micropython-ssd1306/tree/master?tab=readme-ov-file), aimed at streamlining the installation process. In this project, we have removed support for SPI, retaining only the I2C functionality from the original library. The primary focus of this repository is to prepare the library for uploading to PyPI, including renaming it before the upload.

<div align="center">

| Library | Version | Link                                      |
|---------|---------|-------------------------------------------|
| ocks    | 0.4     | [https://pypi.org/project/ocks/](https://pypi.org/project/ocks/) |

</div>

> [!IMPORTANT]  
> All credits and acknowledgements are extended to the contributors and designers of the libraries. For more  information, please visit: [MicroPython Library on GitHub](https://github.com/micropython/micropython-lib/tree/master).



## sdcard-lib

This library is compatible with DualMCU, developed for [MicroPython](https://github.com/micropython/micropython-lib/tree/master). All rights remain with the original author.

<div align="center">

| Library     | Version | Link                                        |
|-------------|---------|---------------------------------------------|
| sdcard-lib  | 0.0.1   | [https://pypi.org/project/sdcard-lib/](https://pypi.org/project/sdcard-lib/) |

</div>

> [!IMPORTANT]  
> All credits and acknowledgements are extended to the contributors and designers of the libraries. For more  information, please visit: [MicroPython Library on GitHub](https://github.com/micropython/micropython-lib/tree/master).


