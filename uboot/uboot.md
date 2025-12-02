!
windows:

  avrdude.exe -c usbasp -p m328p -P usb -F -v -e -U flash:w:"urboot_atmega328p_ee_ce_hw.hex":a 

linux:

  avrdude -c usbasp -p m328p -P usb -F -v -e -U flash:w:"urboot_atmega328p_ee_ce_hw.hex":a


  https://github.com/stefanrueger/urboot

  https://github.com/stefanrueger/urboot.hex/tree/main/cores/minicore/atmega328p/watchdog_1_s/autobaud/uart0_rxd0_txd1/no-led

  https://raw.githubusercontent.com/stefanrueger/urboot.hex/main/cores/minicore/atmega328p/watchdog_1_s/autobaud/uart0_rxd0_txd1/no-led/urboot_atmega328p_ee_ce_hw.hex