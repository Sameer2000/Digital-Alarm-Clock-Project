# Digital-Alarm-Clock-Project

![](assets/screenshot.png)

Use this application ->  https://sameer2000.github.io/Digital-Alarm-Clock-Project/

# DIGITAL ALARM CLOCK 
This is a digital alarm web application where a user can set multiple alarms. The first element of this alarm clock is a display where the real time is being shown. After the current time display, there is a form that takes the input time and when the set alarm button is pressed the input time is added to the upcoming alarms list. When the current time matches any element of the upcoming alarm list, It shows an alert and plays an audio to alert the users. there is a stop alarm button to stop the audio. The elements in upcoming alarm list comes with a delete button which is used to delete that particular alarm form the alarm list.  

# TECHSTACK 
HTML, CSS, JavaScript  

# APPROACH
When a user sets the alarm, the alarm time gets pushed in an array. Their is a function which checks if the current time or the real time is equal to any element in the array. If it does, another function gets called which plays the alarm and gives an alert. On clicking the "Delete Alarm" button the alarm gets removed from the array and the upcoming alarms list.    
