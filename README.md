## Ender-3 S1 STM32F4 board
Used platformio with [some special build flags](https://ufj.ddns.net/blog/marlin/2019/01/07/reducing-marlin-binary-size.html) (also [this](https://www.crosslink.io/marlin-2-0-memory-usage-by-feature/)) to save precious memory to build [Marlin 2.1.2](https://github.com/MarlinFirmware/Marlin)
- T1 + LA
- T1 + UBL + LA
- T13 + UBL + LA
- T13 + LA (HEATER_0_MAXTEMP = 315, BED_MAXTEMP = 135)
- T13 + LA + MPC
- T13 + LA + DACAI (HEATER_0_MAXTEMP = 315, BED_MAXTEMP = 130)
