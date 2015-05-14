SparkFun FreeSoc2
========================================

![FreeSoC2](https://cdn.sparkfun.com//assets/parts/1/0/3/8/5/13229-02.jpg)

[*SparkFun FreeSoC2 (DEV-13229)*](https://www.sparkfun.com/products/13229)

The [FreeSoc2 is SparkFun's PSoC5LP development board](https://www.sparkfun.com/products/13229). It features a full onboard debugger, support for 5V and 3.3V IO voltages, and a CY8C5888AXI-LP096 processor with 256kB of flash, 64kB of SRAM and 2kB of EEPROM. The onboard oscillator can drive the processor at up to 80MHz, and the Cortex-M3 core provides superior performance.

The real power of the PSoC5LP isn't in the processor, however. Wrapped around the processor is a rich analog and digital programmable fabric which can be configured to provide many functions which would otherwise need to be realized in code (lowering system performance) or external circuitry (adding cost and board size). In addition, the highly flexible fabric means that most any function can be routed to most any pin, which makes this a wonderful tool for development and allows board layout errors to be solved, at least temporarily, pretty easily.

Repository Contents
-------------------

* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Arduino support](https://github.com/sparkfun/PSoC_Arduino_Support)** - Support files for adding the FreeSoC2 to the Arduino IDE.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/freesoc2-introduction)** - Basic hookup guide for the FreeSoC2.

Product Versions
----------------
* [DEV-13229](https://www.sparkfun.com/products/13229)- Basic part and short description here

License Information
-------------------
This product is _**open source**_! 

The **hardware** is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

The **code** is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

Collaborators
-------------

Thanks to Jon Moeller, for creating the first FreeSoC board and providing terrific feedback during the development of the FreeSoC2.
Thanks to Cypress Semiconductor, for providing feedback and working with us closely to ensure that the FreeSoC2 was the right product for the time.
