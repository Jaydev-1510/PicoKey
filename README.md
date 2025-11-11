# 🔐 Tiny Passkey — RP2354 Edition

**Tiny Passkey** is a **minimalist hardware passkey** built around the **RP2354** (with 2MB flash) microcontroller — designed to act as a **secure, plug-and-play 2FA / FIDO-like device**. It’s compact, low-power, and 100% DIY-friendly.

---

## 📷 Pictures

![PicoKey](https://github.com/user-attachments/assets/def03033-f218-47a6-96de-18343b5bb70c)

![PicoKey near ruler](https://github.com/user-attachments/assets/f789bd6e-5406-4ff1-865c-d19e272d62de)

---

## ⚙️ Features

* 🧠 **Powered by RP2354** — dual-core ARM Cortex-M33 with hardware crypto engine
* 🔌 **Native USB HID** — works out-of-the-box as a keyboard, security key, or authenticator
* 💾 **On-chip Flash** for compact build
* 🌈 **LED** for status indication

---

## 🚀 Getting Started

1. Flash the firmware from [https://github.com/polhenarejos/pico-fido] to your RP2354 passkey
2. Plug it into any USB port — it’ll enumerate as a passkey device
3. Hack!

---

## 🧩 Hardware

* MCU: **Raspberry Pi RP2354**
* USB: **Built-in PCB connector**
* LED: **GPIO 19**
* Button: **Tact switch for user confirmation**

---

## ⚠️ Disclaimer

This project is for **educational and personal security experimentation**.
Do **not** use it for real banking or sensitive accounts without proper review.

---

## 💡 Inspiration

Inspired by **YubiKey**, but made to be **DIY-friendly**, **open-source**, and **hackable**.
