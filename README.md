# HexaGlow Neon miner

The HexaGlow-Neon-miner is a fully open source hardware Crypto ASIC miner currently under development.

# Goals

direct mining to youre pc over usb or standalone to a pc

-Embedded: low cost, high availability, high reliability, low electricity consumption, high mining power, max profits

-ASIC: based on 6 of the very efficient BM1397 from Bitmain.

-Versatile: solo/pool mining, autotune power/heat/efficiency.

-Open Source: All design files are provided.

# Features

-ESP32-S3-WROOM-1 wifi microcontroller on board.

-TI TPS40305 buck regulator steps down the 5V input to power the BM1397 chips.

-Maxim DS4432U+ current DAC digitally adjusts the BM1397 core voltage from 0.04V to 2.4V for max efficiency.

-TI INA260 power meter measures the input voltage and current of the miner for monitoring the electricity usage.

-Microchip EMC2101 measures the BM1397's internal diode temperature and tunes the fans speed for max powwer and noise reduction.

-SSD1306 Display for Hashrate, Status, Power consumption, etc.

# Status

-The hardware is under development.
-The Neon Miner firmware isn't being developed yet.



If anybody wants to contribute you can message me on discord my id is: Abonion#7517

Credit to Skot for inspiring the project's idea and providing some inforamtion: https://github.com/skot
