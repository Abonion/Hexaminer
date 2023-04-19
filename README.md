# HexaGlow Neon miner

HexaGlow Neon miner is a miner device currently under development that has six BM1397AG ASIC chips that can mine at up to 2400 GH/S with an efficiency of 30J/T. The miner will be able to work completely independently and mine and communicate with the Bitcoin blockchain using the ESP32s integrated Wi-Fi, eliminating the need for an external PC.

The chips communicate via UART to the ESP32-WROOM-1 at speeds of up to 6 Mbit/s. The chips are going to be cooled with a cooler (heatsink and fan) that automatically adjusts the fan speed according to the chips' temperature, providing optimal performance while making it as quiet as possible without losing performance.

There will be an SSD1306 screen that shows the hashrate, difficulty, and temperature (provided data will be according to CGMiner). The miner will adjust the power consumption according to the demand of the chips and the difficulty to save power so that it can reach speeds of up to 2400GH/s with 120 watts or less.

An app will be available that uses Bluetooth connectivity for a more secure and efficient experience. It will allow you to monitor and provide energy consumption and cost-tracking features and will make the device more user-friendly and much more.

Efforts are still underway to improve the device's security while mining, optimize the power consumption, and make it compatible with solar panels. The chips are going to be overclocked to the maximum safe level, and efforts are being made to make it cost less than $250, making it the most affordable miner in the world with such power and efficiency. Additionally, efforts are being made to make the device more portable while still generating minimal heat.
