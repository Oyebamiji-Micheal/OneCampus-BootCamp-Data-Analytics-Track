# OneCampus Cohort 14/Cohort 15 Python Academy Project 

## Project Brief:

Badmus Kwasi is a student of OneCampus enrolled in the Data Science Program. Badmus belongs to a cohort of over 800 students. During the first few bootcamps, Badmus observes the difficulty students in all the cohorts of OneCampus have in knowing their Bootcamp dates and times in their local/county time zones. This difficulty often results in students logging in too early, too late, or totally missing their boot camps. Bootcamp times are always issued in Eastern Standard Time (EST) which is approximately UTC -5. This is the America -New York time. OneCampus has students in all the time zones of the world.

Badmus wants to develop a PYTHON-ONLY application that can be used to convert Bootcamp times from EST to any of the time zones requested by a student. The app should be able to convert the given date and time (Day and Time) to the requested time zone day and time.

The app should be able to store information about upcoming bootcamps by program type (Data Science, Machine learning, and Data Analytics) using python containers ONLY and provide a corresponding list of the schedules in any time zone or country requested by a student. This app must not have any database implemented and should not read from nor save to any file on disk. All data MUST be stored in python code using containers ONLY

As a bonus, if a student provides his/her full name, Country name and time zone, and email address, the app can generate an alert for the student on their computer (no need for an email script) notifying the student 24 hours before their next Bootcamp start time and 2 hours before Bootcamp start time.

Bootcamp Schedules for each of the three programs for the next three months are provided in the Bootcamp Schedule (see attached files in project directory)

Also provided are two files of world time zone times.

One file contains times by country while the second provides times by time zone. This is a list of all the time zone names along with their offset in seconds from UTC and also offset during daylight savings time from UTC. The format of the CSV is simply timezone, offset, offset_dst
 
 
## Project Specifications:

App Capability

* App should hold information about the times in countries of the world (two lists have been provided. One contains 588 Countries times while the other has times for 404 countries)
>- Should therefore be able to tell the current time in any country specified by the user by simply reading the current system time and time zone

* App should hold the time zones and times of the 200 time zones provided

>- Should therefore be able to tell the time zone of any country specified by the user


* When provided the name of a source country and time zone, the app should be able to provide the equivalent time in any specified target country and display its time zone

* App should be able to generate the Bootcamp schedule in the time/timezone of any country specified

* As a bonus, the app should be able to read the current system time and alert the user if any upcoming Bootcamp is less than 24 hours from the current system time

* Additional bonus: Implement code with a database backend and a Graphical User Interphase.

## Files
* [timezones_Detailed_588_Countries.csv](https://github.com/Oyebamiji-Micheal/OneCampus-BootCamp-Data-Analytics-Track/blob/master/Python%20Programing%20Project/timezones_Detailed_588_Countries.csv)
* [timezones_Standard_Times.csv](https://github.com/Oyebamiji-Micheal/OneCampus-BootCamp-Data-Analytics-Track/blob/master/Python%20Programing%20Project/timezones_Standard_Times.csv)
* [BootcampSchedule.xlsx](https://github.com/Oyebamiji-Micheal/OneCampus-BootCamp-Data-Analytics-Track/blob/master/Python%20Programing%20Project/BootcampSchedule.xlsx)
* [Time zones_404_Counries.xlsx](https://github.com/Oyebamiji-Micheal/OneCampus-BootCamp-Data-Analytics-Track/blob/master/Python%20Programing%20Project/Time%20zones_404_Counries.xlsx)
