# Alcohol-Detection-for-cars

We often encounter cases of drunk driving where drivers crash their cars under the influence of alcohol, causing damage to property and life. To address this issue, we propose an innovative system that constantly monitors the driver's breath for alcohol. If alcohol is detected, the system locks the engine, preventing the vehicle from starting. This system uses an Arduino, a PC fan to simulate an engine, an alcohol sensor, and a buzzer.

## Objective of the Project

In today's world, automated systems are essential due to their flexibility, reliability, and accuracy. Automated systems reduce manual operations and meet the increasing demand for safety and efficiency. This project aims to eliminate drunk driving incidents by using an alcohol detection system to prevent intoxicated drivers from operating vehicles.

## How It Works

- **Alcohol Detection Before Starting the Vehicle:**
   - The alcohol sensor is placed on the driver's wheel or another location where it can constantly monitor the driver's breath.
   - If alcohol is detected in the driver's breath, the system locks the engine, preventing the vehicle from starting.
   - The Arduino microcontroller detects the high alcohol signal from the sensor, triggers the buzzer to indicate alcohol detection, and stops the PC fan to simulate engine locking.

- **Alcohol Detection After Starting the Vehicle:**
   - If the driver starts the vehicle without any alcohol detected but consumes alcohol while driving, the sensor detects the alcohol in the breath.
   - The system then locks the engine at that time, stopping the vehicle from accelerating further and allowing the driver to steer to the roadside safely.

## Parts Used

- Arduino UNO
- Breadboard
- 12V PC Fan (to represent an engine)
- Power Supply or Batteries
- Alcohol Sensor MQ3
- Arduino UNO USB Cable
- Jumper Cables (M/M and M/F)
- LEDs
- Relay
- Buzzer

## Hardware Connections

1. Connect the alcohol sensor MQ3 to the Arduino.
2. Connect the 12V PC fan to the Arduino through a relay to simulate engine locking.
3. Connect the buzzer to the Arduino to indicate alcohol detection.
4. Connect LEDs to the Arduino for visual indication.
5. Use jumper cables to connect all components to the breadboard and Arduino.

## Software Configuration

- Program the Arduino using C++.
- Write code to continuously read the alcohol sensor data.
- Implement logic to check if the alcohol level exceeds the predefined threshold.
- If alcohol is detected, trigger the buzzer, stop the fan, and lock the engine using the relay.
- Ensure the system remains active to detect alcohol even after the vehicle starts.

## Future Improvements

- Integrate additional sensors to monitor other safety parameters, such as seat belt usage.
- Implement a voice call feature to alert emergency contacts if alcohol is detected.
- Develop a mobile app or web server to display and store the detected data.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the contributors and the open-source community for providing the libraries and support needed for this project.
