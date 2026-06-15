# Arduino-Based Radar System for Object Detection and Distance Measurement

## 📌 Overview

The Arduino-Based Radar System for Object Detection and Distance Measurement is a low-cost and portable radar-like system that uses an Arduino Uno, HC-SR04 Ultrasonic Sensor, and Servo Motor to detect objects and measure their distance within a 180° scanning range. The detected object's position and distance are visualized in real time using the Processing IDE, creating an interactive radar display.

This project demonstrates the practical application of embedded systems, sensor integration, and real-time data visualization for educational and research purposes.

---

## 🚀 Features

- 180° environmental scanning using a servo motor
- Real-time object detection with an HC-SR04 ultrasonic sensor
- Distance measurement range: 2 cm – 400 cm
- High accuracy: ±1 cm within 200 cm and ±3 cm at 400 cm
- Graphical radar visualization using Processing IDE
- Low-cost and portable design
- Easy-to-build educational project
- Suitable for learning Arduino programming, sensor interfacing, and data visualization

---

## 🛠️ Hardware Components

| Component | Quantity |
|------------|------------|
| Arduino Uno | 1 |
| HC-SR04 Ultrasonic Sensor | 1 |
| SG90 Servo Motor | 1 |
| Jumper Wires | Several |
| Breadboard (Optional) | 1 |
| USB Cable | 1 |
| Computer with Arduino IDE & Processing IDE | 1 |

---

## 💻 Software Requirements

- Arduino IDE
- Processing IDE
- USB Driver for Arduino Uno

---

## ⚙️ How It Works

1. The servo motor continuously rotates the ultrasonic sensor from 0° to 180° and back.
2. The HC-SR04 sensor emits ultrasonic waves.
3. When the waves hit an object, the echo is reflected back.
4. Arduino calculates the object's distance based on the echo return time.
5. Distance and angle data are transmitted to the computer through serial communication.
6. Processing IDE receives the data and displays a real-time radar visualization.

---

## 📊 Performance Specifications

| Parameter | Value |
|------------|--------|
| Detection Range | 2 cm – 400 cm |
| Scan Angle | 180° |
| Distance Accuracy (≤ 200 cm) | ±1 cm |
| Distance Accuracy (400 cm) | ±3 cm |
| Scan Speed | ~2 scans per second |
| Communication | Serial (USB) |

---
 

## 🔌 Circuit Connections

### HC-SR04 Connections

| HC-SR04 Pin | Arduino Pin |
|-------------|-------------|
| VCC | 5V |
| GND | GND |
| TRIG | D10 |
| ECHO | D11 |

### Servo Motor Connections

| Servo Pin | Arduino Pin |
|------------|-------------|
| VCC | 5V |
| GND | GND |
| Signal | D12 |

> Note: Update the pin numbers if your implementation uses different connections.

---

## ▶️ Installation & Usage

### Step 1: Upload Arduino Code

1. Open Arduino IDE.
2. Connect the Arduino Uno via USB.
3. Open the `.ino` file.
4. Select **Arduino Uno** from the board menu.
5. Select the correct COM port.
6. Upload the code.

### Step 2: Run Processing Visualization

1. Open Processing IDE.
2. Open the `.pde` file.
3. Update the serial port if necessary.
4. Click **Run**.
5. Observe the radar visualization on the screen.

---

## 🎯 Applications

- Educational demonstrations
- Embedded systems learning
- Robotics projects
- Obstacle detection systems
- Smart home automation
- Industrial monitoring
- Basic surveillance systems
- Radar technology demonstrations

---

## ⚠️ Limitations

- Performance degrades beyond 300 cm due to ultrasonic signal attenuation.
- Scan speed is limited by servo motor movement.
- Blind spot exists directly behind the sensor.
- Ultrasonic sensors can be affected by environmental conditions such as temperature and surface material.

---

## 🔮 Future Enhancements

- Integration of multiple sensors for wider coverage
- Higher scanning resolution and accuracy
- Wireless communication using Bluetooth or Wi-Fi
- IoT integration for remote monitoring
- Autonomous vehicle obstacle detection
- Smart home automation applications
- Advanced object tracking and classification

---

## 👨‍💻 Author

**Abdullah Anas**  
American International University-Bangladesh (AIUB)

### Connect With Me

- GitHub: https://github.com/mdAbdullahAnas
- LinkedIn:  https://www.linkedin.com/in/md-abdullah-anas-5a4914253/

---

## 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project for educational and research purposes.

---

⭐ If you found this project useful, consider giving the repository a star!
