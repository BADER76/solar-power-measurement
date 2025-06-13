# Solar Power Measurement System 🌞

Welcome to the **Solar Power Measurement System** repository! This project focuses on measuring solar power using an STM32 microcontroller, along with voltage and current sensors. The system features an OLED display for local monitoring and utilizes ThingSpeak for real-time IoT data visualization. 

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Components Used](#components-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Data Visualization](#data-visualization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Project Overview

The Solar Power Measurement System is designed to provide accurate readings of solar energy production. This system can help users monitor their solar panels' performance and optimize energy usage. It integrates various components to create a seamless monitoring experience.

### Key Components:
- **STM32 Microcontroller**: Acts as the brain of the system.
- **Voltage and Current Sensors**: Measure the electrical parameters.
- **OLED Display**: Provides real-time feedback on power metrics.
- **ThingSpeak**: Cloud platform for IoT data storage and visualization.

## Features

- Real-time monitoring of voltage and current.
- Cloud-based data storage for easy access.
- OLED display for immediate feedback.
- User-friendly interface for data visualization.
- Scalable architecture for future enhancements.

## Components Used

1. **STM32 Microcontroller**
   - Powerful and efficient, ideal for embedded systems.

2. **Voltage Sensor**
   - Measures voltage levels from the solar panel.

3. **Current Sensor**
   - Monitors the current flowing through the system.

4. **OLED Display**
   - Displays real-time data and system status.

5. **ThingSpeak**
   - Cloud service for IoT applications, allowing data visualization and analytics.

6. **Power Supply**
   - Provides the necessary power for the components.

## Getting Started

To get started with the Solar Power Measurement System, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/BADER76/solar-power-measurement.git
   cd solar-power-measurement
   ```

2. **Install Required Libraries**
   Ensure you have the necessary libraries installed for STM32 development.

3. **Connect the Hardware**
   Follow the wiring diagram provided in the documentation to connect all components.

## Installation

1. **Hardware Setup**
   - Connect the voltage and current sensors to the STM32.
   - Attach the OLED display for visual feedback.
   - Ensure the ThingSpeak API key is correctly configured in the code.

2. **Software Setup**
   - Open the project in your preferred IDE (e.g., STM32CubeIDE).
   - Upload the firmware to the STM32 microcontroller.

## Usage

Once everything is set up, power on the system. The OLED display will show real-time readings of voltage and current. The data will also be sent to ThingSpeak for cloud monitoring.

### Example Readings
- Voltage: 24.5V
- Current: 3.2A

## Data Visualization

ThingSpeak allows you to visualize the data collected from your solar power system. You can create graphs and dashboards to analyze performance over time.

### Steps to Access Data
1. Visit [ThingSpeak](https://thingspeak.com).
2. Log in or create an account.
3. Navigate to your channel to view real-time data.

## Contributing

Contributions are welcome! If you want to improve this project, feel free to fork the repository and submit a pull request. Please ensure your code follows the project's coding standards.

### How to Contribute
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push to your branch.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to reach out:

- **GitHub**: [BADER76](https://github.com/BADER76)
- **Email**: [your-email@example.com](mailto:your-email@example.com)

## Releases

You can find the latest releases of this project [here](https://github.com/BADER76/solar-power-measurement/releases). Download the necessary files and execute them to get started.

Feel free to check the "Releases" section for updates and new features. 

---

This project aims to provide an accessible way to monitor solar power systems, promoting renewable energy usage. Thank you for your interest in the Solar Power Measurement System! 🌍