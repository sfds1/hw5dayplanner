## Name and live url
Stephanie Kuo Week5 - Day Planner
https://sfds1.github.io/hw5dayplanner/

## Description
This is a planner for a single day.

## What does the app do?
This application allows a user to save tasks for a standard business day which is 9AM to 5PM.

## How does it work?
A user will be able to save tasks in hourly timeslots for the current day that they access the application.  Depending on the time of day, the timeslots will change color. Historical timeslots will be grey.  The current time will be red.  Future times will be green.

## Technologies

## Languages, frameworks, various tools
This application uses JQuery, CSS, HTML, Bootstrap

## Challenges
This application is interesting as in the beginning I was thinking I could dynamically create the hour timeslots to make the code really small.  Maybe there is a way, but I thought about it later and each timeslot needs a unique ID to tie to the tasks entered so that when the information is stored in to local storage, the time and tasks are related.

Moment.js documentation was a lot ot get through.

## Your experience building this app
This application was fun to build.

## What was difficult
Trying to remember all the right syntax.

## What did you learn
I learned more about moment.js, local Storage and traversing the DOM

## How did you go about solving a problem
My tutor was great in helping me start on a resolution to the problems I had.

## Screenshot




## Live app, not code




Required
Clean code - indentation and spacing is correct, console logs, commented-out code and unnecessary comments are removed
Proper file structure - CSS, JS and images are in assets folder, index.html in root folder, file and folder names are not capitalized and don’t contain spaces
README.md - see our MD Guide
Polished UI - the app should look good, be responsive, and fully functional
Uses Moment library to capture date and time information
Application displays timeblocks for standard business hours
Each time block contains a label, an input field, and save button
Clicking on a time block’s save button saves the input text to local storage, allowing the text to persist when the application is refreshed
The current day is displayed at the top of the calendar
Each timeblock is color coded to indicate whether it is in a past, present or future hour
Bonus
Detailed pseudocode - refer to Musa’s example from week 4
Current time is displayed at the top of the calendar (hours, mins, and secs)
Notifications for successful save
Delete buttons on each time block
