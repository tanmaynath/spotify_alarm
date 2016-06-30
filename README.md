# spotify_alaram
Make sure spotify is running. DONT Quit otherwise you have to run the script twice.
Schedule the time using crontab.
crontab -e

MM HH DD MM YYYY osascript spotify_alarm.scpt
eg: 15 6 * * * osascript spotify_alarm.scpt will run the script every morning at 6 15
