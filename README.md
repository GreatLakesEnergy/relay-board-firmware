# relay-board-firmware
Firmware for SESH-RMC Firmware

We are using RFM69Pi for relay driver,
To be able to upload sketches on this module, you will need to modify optBoot bootloader .
Follow this link to modify the bootloader https://wiki.openenergymonitor.org/index.php/RFM69Pi_V3,

Note: RFM69Pi can not be powered by 5v, it uses 3.3V

5V Relay board that we are using trigger the relays when it gets 0V. It uses PNP transistors as switch.

