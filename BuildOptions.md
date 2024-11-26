# Klipper
## SKR Mini E3 V3
[*] Enable extra low-level configuration options
    Micro-controller Architecture (STMicroelectronics STM32)
    Processor model (STM32G0B1)
    Bootloader offset (8KiB bootloader)
    Clock Reference (8 MHz crystal)
    Communication interface (USB (on PA11/PA12))
    USB ids
        (0x1d50) USB vendor ID
        (0x614e) USB device ID
        [*] USB serial number from CHIPID
()  GPIO pins to set at micro-controller startup

## EBB42 1.2V
[*] Enable extra low-level configuration options
    Micro-controller Architecture (STMicroelectronics STM32)
    Processor model (STM32G0B1)
    Bootloader offset (8KiB bootloader)
    Clock Reference (8 MHz crystal)
    Communication interface (USB (on PA11/PA12))
    USB ids
        (0x1d50) USB vendor ID
        (0x614e) USB device ID
        [*] USB serial number from CHIPID
(!PB3)  GPIO pins to set at micro-controller startup

# Katapult
## SKR Mini E3 V3 & EBB42 1.2V
    Micro-controller Architecture (STMicroelectronics STM32)
    Processor model (STM32G0B1)
    Build Katapult deployment application (Do not build)
    Clock Reference (8 MHz crystal)
    Communication interface (USB (on PA11/PA12))
    Application start offset (8KiB offset)
    USB ids
        (0x1d50) USB vendor ID
        (0x6177) USB device ID
        [*] USB serial number from CHIPID
()  GPIO pins to set on bootloader entry
[*] Support bootloader entry on rapid double click of reset button
[ ] Enable bootloader entry on button (or gpio) state
[ ] Enable Status LED