# Relevant code

## Where does the code come from?

The code comes from the example of [Reclaimer Labs](https://www.reclaimerlabs.com/) shared by [GreatScott!](https://www.instructables.com/member/GreatScottLab/)

For more details, please see:

[DIY USB Type-C Power Delivery Trigger Board](https://www.instructables.com/DIY-USB-Type-C-Power-Delivery-Trigger-Board/)


## Can I run this code on Arduino uno, nano, micro or leonardo?

No, they don't have enough SRAM(only 2KB)，It is recommended to use a processor with SRAM of 4KB and above，

## E.g. MCU

| MCU           | SRAM | Has it been tested？ |
| ------------- | ---- | -------------------- |
| STM32F030F4P6 | 4KB  | :yellow_heart:       |
| STM32F072CBT6 | 16KB | 💚                    |
| STM32F103C8T6 | 20KB | :yellow_heart:       |
| ESP8266       | 16KB | 💚                    |

## How can I run this code with stm32 on arduino ide？

Well, please see [Arduino_Core_STM32](https://github.com/stm32duino/Arduino_Core_STM32)

