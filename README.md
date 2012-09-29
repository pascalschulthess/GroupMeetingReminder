# Group Meeting Reminder
Find a full description of the program on [my blog](http://pascalschulthess.de/organizing-weekly-research-group-meetings-with-applescript/370).

## Requirements
Generate a weekly reminder email and add a calendar event for research group meetings

## Design
Reads in a members list file and a message file as well as a date set in iCal to create a new iCal event
a certain amount of days later and a reminder email announcing the upcoming group meeting.

## Interfaces
Apple Mail, iCal, members.txt, message.txt