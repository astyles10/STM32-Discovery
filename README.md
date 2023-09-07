# STM32-Discovery

Peripheral Library: https://www.st.com/en/embedded-software/stsw-stm32065.html

# Links

* Timers
https://embeddedthere.com/stm32-timer-tutorial-using-interrupt/
https://www.digikey.com.au/en/maker/projects/getting-started-with-stm32-timers-and-timer-interrupts/d08e6493cefa486fb1e79c43c0b08cc6

* USART
https://microcontrollerslab.com/uart-usart-communication-stm32f4-discovery-board-hal-uart-driver/
https://deepbluembedded.com/how-to-receive-uart-serial-data-with-stm32-dma-interrupt-polling/

* Sensors
https://www.digikey.com.au/en/products/detail/cui-devices/CUSA-TR80-065-2000-TH68/16579210
https://www.digikey.com.au/en/products/detail/pui-audio-inc/UTR-1440K-TT-R/6071962

* Data structures
https://www.baeldung.com/cs/circular-buffer

* Bluetooth
https://github.com/Jakeler/ble-serial
https://www.martyncurrey.com/hm-10-bluetooth-4ble-modules/#HM-10_Services_and_Characteristics

Setting up Bluetooth connection:

1. bluetoothctl connect 64:69:4E:7B:44:76
2. ble-serial -d 64:69:4E:7B:44:76 -l logfile
3. tail -f logfile
4. minicom -D /tmp/ttyBLE


