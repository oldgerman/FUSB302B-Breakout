# FUSB302B-Breakout

## PCB

![1](https://github.com/oldgerman/FUSB302B-Breakout/blob/master/images/brdview.png)

## Schematic

![2](https://github.com/oldgerman/FUSB302B-Breakout/blob/master/images/schematic.png)

## B.O.M

 please see bom/ibom.html


## Relevant code

### Where does the code come from?

The code comes from the example of [Reclaimer Labs](https://www.reclaimerlabs.com/) shared by [GreatScott!](https://www.instructables.com/member/GreatScottLab/)

For more details, please see:

[DIY USB Type-C Power Delivery Trigger Board](https://www.instructables.com/DIY-USB-Type-C-Power-Delivery-Trigger-Board/)


### Can I run this code on Arduino uno, nano, micro or leonardo?

No, they don't have enough SRAM(only 2KB)，It is recommended to use a processor with SRAM of 4KB and above，

### How can I run this code with stm32 on arduino ide？

Well, please see [Arduino_Core_STM32](https://github.com/stm32duino/Arduino_Core_STM32)

### E.g. MCU

In theory, all MCUs supported by stm32duino support.

| MCU           | SRAM | Has it been tested？ |
| ------------- | ---- | -------------------- |
| STM32F030F4P6 | 4KB  | :yellow_heart:       |
| STM32F072CBT6 | 16KB | 💚                    |
| STM32F103C8T6 | 20KB | :yellow_heart:       |
| ...           | ...  | ...                  |
| ESP8266       | 16KB | 💚                    |

## Pictures

The smallest system board used in the test is based on STM32F072CBT6, for more details, please see: [DarkPill](https://github.com/oldgerman/DarkPill)

<table>
    <td><img src = "images/FUSB302B-EVM.png"</td>
        <td><img src = "images/5V.png"</td>
            <td><img src = "images/9V.png"</td>
</table>


<table>
    <td><img src = "images/12V.png"</td>
        <td><img src = "images/15V.png"</td>
            <td><img src = "images/20V.png"</td>
</table>


## 

## Acknowledgments

-  [GreatScott!](https://www.instructables.com/member/GreatScottLab/)
-  [Reclaimer Labs](https://www.reclaimerlabs.com/) 
- [STM32duno](https://github.com/stm32duino)

