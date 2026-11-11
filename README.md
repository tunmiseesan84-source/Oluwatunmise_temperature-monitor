Temperature Monitor and Alarm Checker

Project Description

This Python project monitors machine temperature by collecting five readings, calculating the highest, lowest and average values, and detecting temperatures above a safe limit of 80°C. It also includes an alarm system, temperature classification (NORMAL, WARNING, CRITICAL) and input validation for reliable monitoring.

What It Does

- Collects five machine temperature readings.
- Stores readings in a Python list.
- Calculates the highest temperature.
- Calculates the lowest temperature.
- Calculates the average temperature.
- Detects temperatures above 80°C.
- Displays an alarm when the safe limit is exceeded.
- Classifies average temperature as NORMAL, WARNING or CRITICAL.
- Allows users to repeat the monitoring process.

How to Run It

1. Install Python 3.
2. Download or clone this repository.
3. Open the project folder.
4. Run the following command:

python temperature_monitor.py

You can also run the program using Pydroid 3 on Android.

Sample Output

TEMPERATURE MONITOR AND ALARM CHECKER

Safe temperature limit: 80.0 °C

Enter temperature reading 1: 40
Enter temperature reading 2: 55
Enter temperature reading 3: 82
Enter temperature reading 4: 60
Enter temperature reading 5: 45

===== TEMPERATURE REPORT =====

Highest temperature: 82.00 °C
Lowest temperature: 40.00 °C
Average temperature: 56.40 °C

ALARM: HIGH TEMPERATURE DETECTED!

Unsafe readings: [82.0]
Safe limit: 80.0 °C

Average temperature condition: NORMAL

Check another set of readings? (y/n): n

Monitoring ended. Thank you.

My Own Twist

I added an average-temperature classification feature.

The program classifies the average temperature into three conditions:

- NORMAL: Below 64°C.
- WARNING: From 64°C to 80°C.
- CRITICAL: Above 80°C.

I also added input validation to prevent invalid entries, such as letters and temperatures below absolute zero.

What I Learned

Through this project, I learned how to use Python functions, loops, lists, conditional statements and input validation. I also learned how programming can be applied to machine monitoring and engineering problems.

Technologies Used

- Python 3
- Pydroid 3 (Android)
- GitHub

Author

Oluwatunmise elijah

ND1 Mechatronics Engineering, YabaTech.
