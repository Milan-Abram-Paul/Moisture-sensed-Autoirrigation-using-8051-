# Moisture-sensed-Autoirrigation-using-8051-
This repository contains the code and circuit design for an automatic irrigation system based on 8051 microcontroller. The system uses a soil moisture sensor to monitor soil conditions and automatically activates a water pump when the moisture level drops below a predefined threshold.

📌 Project Overview

This project implements an automated irrigation system using an 8051 microcontroller and a soil moisture sensor. The system detects the moisture level in the soil and automatically turns the water pump ON or OFF based on the moisture content. This helps in efficient water usage, reducing wastage and ensuring that plants receive the right amount of water.

🔹 Features

Automatic Soil Moisture Monitoring – Continuously checks soil moisture levels.

Pump Control Mechanism – Automatically turns ON the pump when soil is dry and OFF when moisture is sufficient.

Energy Efficient – Saves water and reduces manual intervention.

Microcontroller-Based – Uses the 8051 microcontroller programmed in Embedded C.

LCD Display (Optional) – Displays soil moisture level and pump status.

🔹 Components Used

8051 Microcontroller (AT89S52 / AT89C51)

Soil Moisture Sensor

Relay Module

Water Pump

Power Supply Circuit (5V & 12V)

LCD Display (16x2) - Optional

Resistors, Capacitors, Transistors, and Connecting Wires

🔹 Circuit Diagram

The system is designed to interface the soil moisture sensor with the 8051 microcontroller. The relay module controls the water pump, which is powered ON/OFF based on sensor readings.

Basic Working:

The soil moisture sensor detects the water content in the soil and sends an analog signal.

The signal is converted into a digital signal using an ADC (if needed) and fed to the 8051 microcontroller.

If the soil is dry, the microcontroller activates the relay, turning ON the water pump.

If the soil is moist enough, the relay remains OFF, keeping the pump OFF.

An LCD display (optional) can show real-time status.

🔹 How to Set Up the Project

1️⃣ Hardware Setup:

Connect the soil moisture sensor output to the 8051 microcontroller’s input pin.

Connect the relay module to the microcontroller’s output pin.

The relay module should be connected to the water pump.

Power up the system using 5V for the microcontroller and 12V for the water pump.

2️⃣ Software Setup:

Install Keil uVision (for writing and compiling the Embedded C program).

Install Proteus (for circuit simulation, if needed).

Write the program in Embedded C.

Compile the code and generate the HEX file.

Flash the HEX file to the 8051 microcontroller using a programmer (e.g., USBASP, Flash Magic).

🔹 Code Explanation

The system is programmed in Embedded C, where:

The soil moisture sensor data is read.

The microcontroller makes decisions based on moisture levels.

The relay and pump are controlled accordingly.

The LCD (if used) displays real-time moisture levels and pump status.

🔹 How to Run the Project

Power on the circuit.

The microcontroller reads the moisture level and checks the threshold.

If the soil is dry, the water pump turns ON automatically.

If moisture is adequate, the pump remains OFF.

The system continuously monitors the soil moisture and controls irrigation accordingly.

🔹 Applications

✅ Smart Agriculture – Efficient irrigation for crops.
✅ Home Gardening – Automatic watering for plants.
✅ Greenhouse Automation – Optimal moisture control.
✅ Water Conservation Projects – Reduces water wastage.

🔹 Future Enhancements

🔹 Implement IoT connectivity for remote monitoring via a mobile app.
🔹 Add temperature & humidity sensors for improved irrigation control.
🔹 Integrate a solar-powered system for eco-friendly operation.

🔹 Repository Contents

📂 Source Code – Embedded C program for 8051 microcontroller.
📂 Circuit Diagram – Complete schematic for hardware connections.
📂 Documentation – Explanation of project setup, working, and applications.
