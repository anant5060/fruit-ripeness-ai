# Fruit Ripeness Detector 🍌🥭

This is a web-based AI system for detecting the ripeness of fruits (e.g. mango) using a Teachable Machine model and a webcam.

## Features
- Real-time webcam-based classification (ripe/unripe)
- Sends prediction to ESP32 via Web Bluetooth
- Fully works in browser (no install required)

## Live Demo
[Click here to open](https://anant5060.github.io/fruit-ripeness-ai/)

## How to Use
1. Open the demo in Google Chrome
2. Click **Start AI Model**
3. Click **Connect BLE** to connect to your ESP32
4. Hold fruit in front of the webcam and observe the results

## Files
- `index.html` — AI + BLE integration
- `model.json`, `metadata.json`, `weights.bin` — Teachable Machine model files

## Credits
Built with ❤️ using TensorFlow.js and ESP32 BLE.
