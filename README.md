# Automeet

#### Update  (Dec 2023)
This probably won't work for anyone but me because the images that are getting recognized were specific to the version of Google Chrome and Google Meet I used in March 2020. It worked then, probably won't work now without significant refactoring, because of UI updates to applications, account specificity, device driver permissions (and probably more).

Automeet is a bot (Python program with some level of spatial and temporal awareness) which attends Google Meets for you. A logged in Google user can attend college lectures by inputting a timetable in a JSON file. This script uses image recognition and emulates human input using pyautogui and win32api. Meetings are exited automatically when present time exceeds meeting end time.

### Configuration variables

'add_to_url': Hardcoded variable in Python script. Must check '?authuser=var' in URL from Google Meet meeting URL opened in Chrome and accessing Meet homepage with preferred login (default = 2). 


xp: list of extra parameters to find in window title to get window_id if meetid is not found in title

daystarttime=:	#efines day start time to not have entire program run before start time (default = 08:00)

dayendtime: when do all classes end, to stop program (default = 17:00)

ttpath: text file with timetable (default = "\timetable.txt")

Dependencies:
pyautogui
pywin32

# Measurement dependency of Turing tests

My professor didn't take an attendance roll-call, so simply joining and exiting the Google Meet video conference was enough to make him think I (the human) joined. Instead a very simple program joined it. Automeet barely has awareness and is an algorithm, yet it was enough to convince my professor that I'd joined the class. Simply because my professor did not measure enough parameters to ascertain if it was me or not. A simple roll-call would have sufficed for the professor to suspect the human had not joined the conference. But this lack of measurement introduced possibility. Possibility in what we're measuring to be human. I don't believe Automeet passes the Turing test of English. But it did fool my professor into thinking the program was a human. It passed a limited measurement Turing test. 

by Noorul

# Bots 4 U Consultancy

If you'd like a human coder to implement and maintain this project within your organization's codebase, we have yearly contracts. Contact us at manonthemoon13131@gmail.com.
