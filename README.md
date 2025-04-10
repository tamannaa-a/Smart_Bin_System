# Smart_Bin_System
Designed a prototype of a smart bin system that uses sensors to predict the bin levels to manage waste. The buzzer is placed inside the bin which is triggered when the bin is full and then generates a sound.

Overview

- Simulates random bin fill levels between 0% to 100%.
- Raises an alert if the fill level crosses a defined threshold (default: **80%**).
- Outputs results in the **Serial Monitor**.

How It Works

- Prints each simulated reading to the Serial Monitor.
- If bin level ≥ 80%, it shows: `ALERT: Bin Full!`
- Otherwise, it shows: `Bin OK`

Simulation Details
1] Generates 10 readings
2] 1-second delay between each reading using delay(1000)

Tools:
TinkerCad,
Wokwi,
Arduino IDE,
MatLab

