# PathFinder
Pathfinder Flight Computer
Pathfinder is a compact, lightweight flight computer designed for experimental model rocketry payload bays. Powered by the ESP32-S3 XIAO SEED STUDIO, it specializes in high-accuracy barometric altitude tracking, real-time telemetry, and critical flight phase detection (such as apogee calculation) for model rocket launches.

Features
Barometric Altitude Tracking: Uses a high-precision digital barometer to sample ambient pressure and calculate real-time relative altitude changes.

Apogee Detection: Implements a noise-filtered peak-detection algorithm to accurately log the exact maximum altitude before descent.

Ultralight Form Factor: Optimally sized for minimal footprint, fitting seamlessly into tight custom-engineered payload bays.

Low-Power Logging: Efficient power management utilizing the ESP32-S3 architecture to ensure stable data logging throughout the launch window.

Tech Stack & Hardware
Hardware
MCU: ESP32-S3 XIAO SEED STUDIO WITH B2B CONNECTORS FOR LORA

Primary Sensor: BMP280

Secondary Sensors: LSM6DS3 , BN-180 GPS

Power: 3.7V LiPo battery input via onboard management

Software & Tooling
Language: C++

Environment: PlatformIO / Arduino Framework

Core Libraries: Wire (I2C communication), SPI, custom filtration libraries
