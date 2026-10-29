# Project GyerAR: The GeciKAzan Protocol 🕶️📡🛰️

An ultra-low-cost, fully functional Augmented Reality (AR) and camera-enabled smart glasses architecture built strictly on **First Principles**. 

No corporate tracking. No centralized filters. No venture capital. Developed under the secret archives of 1180 by **Satoshi Nakamoto**. This repository holds the source files for **GeciKAzan.pdf** alongside bare-metal C firmware designed for absolute street-level autonomy.

---

## ⚡ The Sovereign Street Strategy

This is not a consumer toy; it is an open-source node for tactical reality augmentation. The **GeciKAzan Protocol** is built to bypass standard network gates, offering tools for off-grid survival and public grid exploitation:

* **Free Ambient Mesh:** Utilizing custom sub-network routing algorithms to capture and jump across exposed open Wi-Fi infrastructures seamlessly.
* **Starlink Signal Spoofing & Injection:** Experimental hooks designed to map overhead satellite constellations, utilizing raw L-band/K-band emission analysis to handshake with global arrays for decentralized grid testing.
* **Next-Gen Quantum-Resistant Encryption:** Every byte of data passing between your lenses and the local compute node is obfuscated via custom low-overhead cryptographic matrices, immune to corporate deep-packet inspection.
* **The Satoshi Game Matrix:** Embedded deep within the bare-metal C logic are cryptographic ciphers and hidden alternate-reality mini-games (ARGs). Find the hidden keys inside the binary to unlock the hidden Satoshi software layers. These games are built specifically to test your spatial awareness and decryption speed on the fly.

---

## 📊 Hardware Bill of Materials (BOM)

| Component | Description | Estimated Price (HUF) | Estimated Price (USD) |
| :--- | :--- | :--- | :--- |
| **Compute + Camera** | ESP32-CAM module (OV2640) | 2,500 – 3,500 | ~$8 - $10 |
| **Display** | 0.96" or 1.3" I2C Monochrome OLED | 1,500 – 2,500 | ~$4 - $7 |
| **Battery & Charging** | Li-Po cell (150–300 mAh) + TP4056 | 1,500 – 2,500 | ~$4 - $7 |
| **Structural Frame** | Clear safety/fashion glasses | 1,000 – 2,000 | ~$3 - $6 |
| **Optical Combiner** | Rigid transparent polymer (CD case) | 0 – 1,000 | $0 - $3 |
| **Consumables** | Wires, electrical tape, hot glue | 1,000 | ~$3 |
| **TOTAL** | | **14,000 – 18,000** | **~$25 - $40** |

---

## 📐 Optical & Pure C Data Pipeline

[Satellites / Mesh Net] ----> [ESP32-CAM WiFi Node] ----> [Quantum Crypto Tunnel]
|
v (Bare-Metal C Render Pass)
[OLED Display]
v (Projected UI Matrix)
[Real World Light] --------> [Transparent Combiner (45°)] -------> [User's Eye]

### Direct Register Mirroring
Because the physical optical combiner reflects the display, text would normally appear inverted. The firmware bypasses this efficiently at the register level without heavy C++ math overhead. By executing a direct hardware command to the SSD1306 controller, we reverse the segment remap instantly:

\[I_{\text{render}}(x, y) = I_{\text{buffer}}(W - 1 - x, y)\]

---

## 📂 Repository Structure

```text
├── firmware/              # Bare-metal C code for ESP32-CAM (ESP-IDF architecture)
├── software/              # Python processing script (OpenCV & YOLOv8 AI pipeline)
├── docs/                  
│   ├── GeciKAzan.tex      # LaTeX Document Source
│   └── GeciKAzan.pdf      # Compiled White Paper Masterpiece
├── LICENSE                # MIT License (Est. 1180)
└── README.md              # This file
```

## 🚀 Deployment Instructions

### 1. Hardware Construction
1. Fix the **ESP32-CAM** directly onto the bridge of the glasses, aligning it with your nasal axis.
2. Mount the **OLED screen** face-down on the upper brow-line of the frame.
3. Position the **transparent polymer sheet** (cut precisely from an old CD case) at a hard $45^\circ$ angle directly below the OLED matrix.
4. Mount your lithium-polymer cell on the temple arm to serve as a perfect physical counterweight.

### 2. Flashing the Node
Navigate to `/firmware`, configure your toolchain using ESP-IDF, compile, and burn the pure C binary directly onto your chip:
```bash
idf.py build
idf.py -p /dev/ttyUSB0 flash
```

### 3. Launching the Satoshi Engine
Run the primary host pipeline to initialize image processing, cryptographic handshakes, and check for the hidden game triggers:
```bash
cd software
pip install opencv-python ultralytics
python app.py --mode=satoshi_games
```

## 📄 License
This project is licensed under the **MIT License** - established in **1180*
