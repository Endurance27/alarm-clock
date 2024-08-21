# alarm-clock
Python Alarm Clock
This is a simple Python script that functions as an alarm clock. The script allows you to set an alarm for a specific time, and it will play an alarm sound when the specified time is reached.

Features
Set an alarm for a specific hour and minute.
Choose between AM and PM for setting the time.
Plays an alarm sound when the set time is reached.
Requirements
Python 3.x
Pygame library
Installation
Clone the Repository (if applicable):

bash
Copy code
git clone https://github.com/yourusername/repository-name.git
cd repository-name
Install Pygame:

You need to have the pygame library installed. You can install it using pip:

bash
Copy code
pip install pygame
Alarm Sound:

Make sure you have an alarm sound file named alarm.wav in the same directory as the script. This sound file will be played when the alarm goes off.

Usage
Run the script:

bash
Copy code
python alarm_clock.py
Enter the alarm time when prompted:

Hour: Enter the hour in 12-hour format (e.g., 1-12).
Minute: Enter the minute (e.g., 0-59).
AM/PM: Specify whether the time is AM or PM.
The script will confirm the alarm time and wait until the specified time is reached.

When the alarm time is reached, the script will play the alarm.wav sound file and print "Alarm ringing...".

Example
bash
Copy code
Enter alarm hour (1-12): 7
Enter alarm minute (0-59): 30
Enter am/pm: am
Alarm set for 07:30:00
Notes
The script checks the time every 30 seconds, so there may be a slight delay when the alarm triggers.
The script will continue to run until the alarm time is reached and the alarm sound is played.
