# The Blue ESP - WavyChat

<div align="center">
  <h3 align="center">!ORIGINAL FIRMWARE!</h3>
  <img src="https://dwdwpld.pages.dev/theblueespwavychat.png" alt="ESP32-BlueJammer">
</div>

<img src="https://dwdwpld.pages.dev/wavychat-chat.png" alt="Wavy Chat Preview" style="display: block; margin: 20px auto;">

---

## About This Project

You can learn more about the Blue ESP on its official store: [The Blue ESP](https://datechlabs.com/products/the-blue-esp-pre-order)

This repository contains the original firmware for "The Blue ESP" PCB. The firmware enables a wireless chat system using an ESP32 board in combination with two nRF24L01 transceiver modules. This project is ideal for enthusiasts looking to explore wireless communication in a simple yet practical application.

### Features
- Wireless communication via nRF24L01 modules.
- Customizable username feature for personalized chatting.
- Simple and user-friendly interface via the Serial Monitor.
- endless devices can communicate with each other

### Hardware Requirements
- **[The Blue ESP](https://datechlabs.com/products/the-blue-esp-pre-order)** by [@donanontech](https://github.com/DonAnonymousio) and [@emensta](https://github.com/emenstanougat).
- 2x nRF24L01+ Modules.
- data-USB cable for programming the ESP32.
- Arduino IDE installed or any other serial monitor (web, etc.).

---

## Installation

1. The Blue ESP firmware can be conveniently flashed via the [webflasher](https://the-blue-esp-wavychat.pages.dev).

---

## How to Use

1. Power on the ESP32 module with the flashed firmware.
2. Open the Serial Monitor (set baud rate to **9600**) in the Arduino IDE or your serial monitor (web, etc.).
3. Press the **EN** button on the ESP32 to reboot it.
4. Enter a username when prompted.
5. Start chatting by typing your message and pressing Enter.
6. Messages will be transmitted wirelessly to other devices running the same firmware.

---

## Screenshots

Below are screenshots showcasing the functionality of the firmware:

- **Serial Monitor with Chat Messages:**
  ![Wavy Chat Preview](https://dwdwpld.pages.dev/wavychat.png)

---

## Credits

- **Firmware Developer:** [@emensta](https://github.com/emenstanougat)
- **PCB Designer:** [@donanontech](https://github.com/DonAnonymousio)

---

## License

This project is licensed under the MIT License. See `LICENSE` for more information.

---

## Feedback and Contributions

Feel free to open an issue or submit a pull request for suggestions and improvements. Your feedback is valuable!
