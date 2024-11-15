# Break Time
## Water reminder notification

-  #pip install plyer

This line is a comment, not code to be executed.
It's a Python package installation command that you'd run in your terminal or command prompt.
plyer is a Python module used to interact with various device features, including notifications.
-  from plyer import notification import time

from plyer import notification: This line imports the notification module from the plyer package. This module provides functions to display system notifications.
import time: This line imports the time module, which provides functions for working with time, such as pausing the execution of the script.
-  def show_notif():

This line defines a function named show_notif. This function will be responsible for displaying the notification.
-  notification.notify(title="Time to take a break", message="Maintain optimal hydration for peak performance.Drink water!", timeout=20)

This line calls the notify function from the notification module to display a notification.
title="Time to take a break": Sets the notification's title.
message="Maintain optimal hydration for peak performance. Drink water!": Sets the message content of the notification.
timeout=20: Sets the duration (in seconds) for which the notification will be displayed.
-  def main():

This line defines the main function, which is the script's entry point.
-  while True:

This line starts an infinite loop. The script will continue to run until it's manually stopped.
-  show_notif()

This line calls the show_notif function to display a notification.
-  time.sleep(3600)

This line pauses the execution of the script for 3600 seconds (1 hour).
-  if __name__=="__main__":

This condition checks if the script is being run directly (not imported as a module).
-  main()

If the condition is true, the main function is called to start the notification loop.
Essentially, this script sets up a recurring notification to remind the user to take a break and drink water every hour.

<br>
<p align="center">
<img src="https://github.com/ShubhangiChawla/Break-Time/blob/main/Notification%20Water%20Reminder.png">
</p>
