# proj8-free_times
Snarf appointment data from a selection of a user's Google calendars and calculate times
they are free.

## Author: Taylor Scott

## Contact: tscott7@uoregon.edu

## Program Description:

This project takes a date and time range before redirecting the user to sign into their 
google account. We then use their google calendar information to find out when they are 
'busy' between the target date and time range. The client then prints out the events 
where the user is 'busy' within the time range, accounting for transparent events as well.
I also humanized the dates similar to project 6 so that it says their event is in x amount
of days as well as the date in ISO form. It then calculates and prints out the times the 
client is 'free' within the time range. We will use this in the next project to calculate
when multiple users are 'free' within a given time range.