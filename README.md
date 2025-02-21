# Raspberry Pi 5 Datalogger & Display for Electric Go-Kart

To achieve full functionality, the system must:

	   Enable Communication via CAN Bus:
	      - Implement a CANOpen library to facilitate reliable data exchange between the Raspberry Pi, SEVCON motor controller, and BMS.
	      - Utilize a Waveshare CAN HAT adapter to establish a robust CAN Bus connection for vehicle telemetry.

	   Data Logging & Storage:
	      - Continuously record real-time performance metrics from both the BMS and SEVCON.
	      - Store collected data in non-volatile memory to ensure retention across power cycles for future analysis and debugging.

	   Real-Time Data Processing & Display:
	      - Process incoming telemetry to extract relevant insights for the driver.
	      - Design an intuitive graphical interface to display critical parameters such as battery voltage, current draw, motor temperature, and speed.
	      - Ensure data visualization is clear, readable, and optimized for an HDMI display.

# Long-Term Goals

	   Driver Input & Dynamic Control:
	      - Expand the system’s capabilities to manage driver input signals, such as throttle position and brake force.
	      - Implement logic to adjust motor and battery settings dynamically based on driving conditions.
	      - Enable real-time parameter adjustments via the CAN network to optimize performance, efficiency, and safety.
