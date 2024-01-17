This Python script continuously monitors the position of the International Space Station (ISS) and sends an email notification when it passes directly overhead during nighttime. The script utilizes the requests library to retrieve ISS data and the smtplib library to send email alerts.

Features

1. Monitors ISS position using the Open Notify API

2. Detects nighttime using the Sunrise Sunset API

3. Sends email alerts to specified email address

4. Continuously runs in the background to provide real-time ISS notifications

Usage

The script will run indefinitely, checking for ISS overhead passes every minute. Upon detecting an ISS flyover during nighttime, it will send an email notification with the subject "Look Up!!" and the message "The ISS is above you in the sky!"
