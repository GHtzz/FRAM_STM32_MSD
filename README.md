# FRAM_STM32_MSD
A mass storage device using FRAM based on a STM32 MCU.

# Milestones
* Implament MSD using STM32CubeMX and STM32IDE, on the STM32F0 discovrt board and build int flash
* POC with external flash
* Order FRAM and implemnt on discovery board
* create castume board, trying to use better suited MCU.
* board bringup and tests
* mv FW to Rust  

# Notes
* RSA-4092 size
| ------------- || PEM (Base64)  | GPG (ASCII-armored PGP)|
| ------------- || ------------- | ------------- |
|Public Key     || ~800–900 bytes | ~3.1 KB |
|Private Key    || ~1700–1800 bytes | ~6.8 KB |

Private Key		PEM - does not include metadata

# Parts
## MCU options
* STM32F072 (current ST discovery kit)
* STM32F042K6

## FRAM


# Resources
* [MSC using RAM](https://embetronicx.com/tutorials/microcontrollers/stm32/stm32-usb-device-msc/)
* [MSC using FLASH](https://embetronicx.com/tutorials/microcontrollers/stm32/stm32-usb-device-msc-using-flash-memory/)
