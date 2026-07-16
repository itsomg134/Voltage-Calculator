# Voltage-Calculator

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML](https://img.shields.io/badge/HTML-5-orange.svg)
![CSS](https://img.shields.io/badge/CSS-3-blue.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)
![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)

**A comprehensive, user-friendly voltage and electrical calculator with both web and CLI interfaces**

[Live Demo](#) · [Report Bug](#) · [Request Feature](#)

</div>

---

## About The Project

The **Voltage Calculator** is a versatile electrical engineering tool designed to simplify complex circuit calculations. Whether you're a student learning Ohm's Law, a hobbyist working on electronics projects, or a professional engineer, this calculator provides instant, accurate results for a wide range of electrical parameters.

### Why This Calculator?

- **Educational**: Perfect for learning and understanding electrical relationships
- **Professional**: Reliable calculations for real-world applications
- **Accessible**: Available as both a web app and command-line tool
- **Comprehensive**: Covers all basic electrical formulas in one place

---

## ✨ Features

### Core Functionality
- ✅ **Ohm's Law Calculations**: Voltage, Current, Resistance
- ✅ **Power Calculations**: Multiple power formulas (P = VI, P = I²R, P = V²/R)
- ✅ **Voltage Divider**: Calculate output voltage for series resistors
- ✅ **Power from Different Parameters**: Flexible input options
- ✅ **Series/Parallel Support**: Calculate total resistance and voltage drops

### User Experience
- 🎨 **Modern UI**: Clean, responsive web interface with gradient design
- 📱 **Mobile-Friendly**: Works on all devices
- ⌨️ **Keyboard Support**: Enter key for quick calculations
- 🔄 **Real-time Updates**: Dynamic formula display
- 🧹 **Clear Function**: Easy reset of all fields
- ⚡ **Instant Results**: No page reloads needed

### Technical
- 🐍 **Python CLI**: For terminal enthusiasts and automation
- 🌐 **Pure HTML/CSS/JS**: No dependencies, runs offline
- 🔒 **Client-Side**: All calculations done in browser (privacy-friendly)
- 📊 **Precision**: Results displayed to 4 decimal places

---

## 🖥️ Screenshots

### Web Interface
<div align="center">
  <img src="screenshots/web-interface.png" alt="Web Interface" width="600"/>
  <br>
  <em>Modern, responsive web calculator interface</em>
</div>

### Python CLI
<div align="center">
  <img src="screenshots/python-cli.png" alt="Python CLI" width="500"/>
  <br>
  <em>Command-line interface with interactive menu</em>
</div>

---

## 🚀 Getting Started

### Prerequisites

- **Web Version**: Any modern web browser (Chrome, Firefox, Safari, Edge)
- **Python Version**: Python 3.7 or higher

### Web Version

1. **Download the HTML file**:
   ```bash
   git clone https://github.com/yourusername/voltage-calculator.git
   cd voltage-calculator
   ```

2. **Open in browser**:
   - Double-click `voltage-calculator.html`
   - Or right-click and select "Open with" your preferred browser

3. **No installation needed** - it's ready to use!

### Python Version

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/voltage-calculator.git
   cd voltage-calculator
   ```

2. **Run the script**:
   ```bash
   python voltage_calculator.py
   ```
   
   For the voltage divider calculator:
   ```bash
   python voltage_divider.py
   ```

3. **Make it executable** (Linux/Mac):
   ```bash
   chmod +x voltage_calculator.py
   ./voltage_calculator.py
   ```

---

## 📖 Usage Guide

### Web Calculator

1. **Select Calculation Type**:
   - Voltage: V = I × R
   - Current: I = V / R
   - Resistance: R = V / I
   - Voltage from Power: V = √(P × R)
   - Current from Power: I = √(P / R)

2. **Enter Values**:
   - Input the required parameters
   - Values can be integers or decimals

3. **Click Calculate** or press **Enter**

4. **View Results**:
   - Result appears in the highlighted box
   - Shows the calculated value with unit

5. **Clear All** to reset fields

### Python CLI

1. **Run the script**
2. **Select calculation type** (1-8)
3. **Enter required values** when prompted
4. **View formatted results**

#### Example Usage:

```bash
$ python voltage_calculator.py
==================================================
⚡ VOLTAGE CALCULATOR
==================================================

Choose what to calculate:
1. Voltage (V = I × R)
2. Current (I = V / R)
3. Resistance (R = V / I)
4. Voltage from Power (V = √(P × R))
5. Current from Power (I = √(P / R))
6. Power (P = V × I)
7. Power from Voltage & Resistance (P = V² / R)
8. Power from Current & Resistance (P = I² × R)

Enter choice (1-8): 1
Enter Current (I) in Amperes: 2
Enter Resistance (R) in Ohms: 10

✅ Voltage (V) = 20.0000 Volts
```

### Voltage Divider Calculator

```bash
$ python voltage_divider.py
==================================================
🔌 VOLTAGE DIVIDER CALCULATOR
==================================================
Enter Input Voltage (V_in): 12
Enter R1 (Ohms): 1000
Enter R2 (Ohms): 2000

📊 Results:
  Output Voltage (V_out) = 8.0000 V
  Voltage across R1 = 4.0000 V
  Voltage across R2 = 8.0000 V
  Total Resistance = 3000.0000 Ω
  Current = 0.004000 A
```

---

## 📐 Formulas Supported

| Calculation | Formula | Unit |
|------------|---------|------|
| **Ohm's Law** | | |
| Voltage | V = I × R | Volts (V) |
| Current | I = V / R | Amperes (A) |
| Resistance | R = V / I | Ohms (Ω) |
| **Power Formulas** | | |
| Power (VI) | P = V × I | Watts (W) |
| Power (V²R) | P = V² / R | Watts (W) |
| Power (I²R) | P = I² × R | Watts (W) |
| Voltage from Power | V = √(P × R) | Volts (V) |
| Current from Power | I = √(P / R) | Amperes (A) |
| **Voltage Divider** | | |
| Output Voltage | V_out = V_in × (R₂ / (R₁ + R₂)) | Volts (V) |
| **Resistance** | | |
| Series | R_total = R₁ + R₂ + ... | Ohms (Ω) |
| Parallel | 1/R_total = 1/R₁ + 1/R₂ + ... | Ohms (Ω) |

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place! Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Development Ideas

- [ ] Add graph visualization for circuit analysis
- [ ] Support for AC circuits (impedance, reactance)
- [ ] Circuit simulation features
- [ ] Unit conversion (kΩ, mΩ, etc.)
- [ ] Save/export calculation history
- [ ] Dark mode for web interface
- [ ] Multi-language support

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📞 Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/voltage-calculator](https://github.com/yourusername/voltage-calculator)
