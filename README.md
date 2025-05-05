# EMF Detector with OLED Display

This project is a simple yet interactive **Electromagnetic Field (EMF) Detector** built using an Arduino. It reads analog EMF data and provides visual and audio feedback based on the signal strength.

## Features

- 📊 **Real-Time EMF Level Display** on a 128x64 OLED (SSD1306)
- 🌊 **Animated Waveform** representing signal strength
- 🚦 **LED Indicators** (Green, Yellow, Red) for low, medium, and high EMF
- 🔊 **Buzzer Alerts** based on EMF intensity
- 🔌 Powered by an analog EMF sensor connected to an analog pin

## Hardware Requirements

- Arduino Uno or compatible board  
- SSD1306 OLED Display (128x64, I2C)  
- EMF Sensor (analog output to A2)  
- 3 LEDs (Green, Yellow, Red)  
- 1 Buzzer  
- Jumper wires and breadboard  

## Wiring Overview

| Component     | Arduino Pin |
|---------------|--------------|
| OLED SDA      | A4 (Uno)     |
| OLED SCL      | A5 (Uno)     |
| EMF Sensor    | A2           |
| Green LED     | D2           |
| Yellow LED    | D3           |
| Red LED       | D4           |
| Buzzer        | D5           |

## Installation

1. Install required libraries:
   - `Adafruit_SSD1306`
   - `Adafruit_GFX`

2. Upload the code to your Arduino board.

3. Power the Arduino and observe EMF levels visually and audibly.

## License

This project is open-source under the MIT License.  
© 2025 Javier Siliacay

---

**Note:** This is an educational and experimental project. EMF values are relative and not calibrated for scientific accuracy.
