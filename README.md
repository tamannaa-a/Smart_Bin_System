# Smart Bin System – Intelligent Waste Monitoring using Sensors
An innovative prototype to predict bin fill levels and manage waste effectively using sensor-based alerts. This system aims to enhance smart city infrastructure by automating the waste monitoring process using simple yet effective embedded logic.

🚀 Project Overview
The Smart Bin System simulates the working of a real-world smart waste bin by:
* Simulating random bin fill levels ranging from 0% to 100%.
* Raising alerts when the fill level exceeds a critical threshold (default: 80%).
* Triggering a buzzer as an audio warning when the bin is full.
* Displaying messages on the Serial Monitor for easy monitoring.

🔍 How It Works
Simulation Loop:
* Generates 10 random bin level readings.
* Includes a 1-second delay between each reading (delay(1000)).

📊 Monitoring Output:
* If bin level ≥ 80% → ALERT: Bin Full!
* Else → Bin OK

🔊 Buzzer Activation:

Buzzer triggers when bin is full to notify for immediate attention.

🧪 Simulation Tools

This project has been simulated and visualized using the following tools:

* TinkerCad-	Circuit Simulation & Visualization
* Wokwi-	Online Arduino Simulator
* Arduino IDE-	Code Development & Serial Monitoring
* MATLAB-	Data Visualization & Analysis (optional extension)

🛠️ Setup Instructions

Clone this repository:
* git clone https://github.com/tamannaa-1/smart_bin_system.git
* Open the project in Arduino IDE or upload it to Wokwi / TinkerCad.
* Simulate the circuit and monitor the output via Serial Monitor.
