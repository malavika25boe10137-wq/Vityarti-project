# Advanced Fall&Vitals Alert System

# Overview
This project is a simple Python script designed to detect patient falls and abnormal heart rates using user-entered data that simulates sensor input. The code prompts for G-force (to detect falls), stillness (to confirm immobility following impact), and pulse rate (to assess patient condition). It aims to provide basic alerts for critical situations, such as detected impacts, confirmation of falls, and abnormal heart pulse rates.

# Features
Detects impact by checking G-force above a set threshold.

Confirms a fall if stillness below a minimum is detected after impact.

Monitors heart rate and alerts for potentially dangerous readings.

Simple user prompts allow simulation and manual testing.

Clear on-screen alerts for critical events (fall, abnormal pulse, normal activity).

# Technologies/Tools Used
Python 3+

Standard Python libraries (input, basic arithmetic and logic)

Runs as a command-line script; no external dependencies required.

# Steps to Install & Run the Project
Ensure you have Python 3 installed on your system.

Copy the code to a file named fall_pulse_detection.py.

Open a terminal or command prompt.

Navigate to the folder containing fall_pulse_detection.py.

Run the script using:

text
python fall_pulse_detection.py
# Instructions for Testing
When prompted, enter a G-force value:

Enter a number greater than 2.5 to simulate significant impact.

Enter a number less than or equal to 2.5 for normal activity.

If impact is detected:

Enter a stillness G-force value. Enter less than 0.2 to confirm fall.

Enter a heart rate value:

Enter less than 50 or greater than 120 to trigger a critical pulse alert.

Enter between 50 and 120 for a normal pulse.

Observe outputs to verify correct alert logic (Fall Confirmed, Critical Pulse Alert, Pulse Normal, etc.).

