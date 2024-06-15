# Controlling-on-board-LED-of-STM32U545RE-Q-through-UART-communication-protocol
Following repository contains HAL C code for controlling the on-board LED of STM32U545RE-Q microcontroller through UART communication protocol.
. Only the main source files are added in this repository as the rest of the files are generated automatically by the STMCubeIDE.
The target microcontroller - STM32U545RE-Q is selected in the STMCubeMX, matching the hardware.
In this repository, the reception of messages through UART is initialized as an interrupt.
Where, in the serial console, when "LED ON" is written, the on-board LED of the microcontroller turns on.
Similarly, for "LED OFF", the on-board LED turns off, indicating the transmission and reception of messages between the microcontroller and the console through UART protocol.
