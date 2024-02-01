This is a basic reminder app which takes in data(Date, Time and Message) from the user and notifies the user on the given date and time.

In this app, I have used Room Database for storing the data of the reminders.

The user is being notified by a notification which contains the message entered by the user. 
We have been using AlarmManager which fires a PendingIntent which in turn call a BroadcastReciever that creates a notification for the user with the message.
