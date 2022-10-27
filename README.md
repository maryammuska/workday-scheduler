# workday-scheduler

## Description:
This is a simple calendar application that allows a user to save events for each hour of their work day.

## Application Functionality:
When the application is launched, the current date is shown at the top of the page. When the user scrolls down, the user can see time blocks from 9 AM to 5 PM. Each time block is color-coded to indicate whether it is in the past, present or future. The user can click into a time block and enter an event. When the save button is clicked for a time block, the event text is saved in local storage and can be retrieved across browser sessions.

## Features
HTML
CSS
Bootstrap
jQuery
Moment.js

Screenshot of app:
<img width="686" alt="Workday Scheduler" src="https://user-images.githubusercontent.com/101304518/198382326-28a4ec92-f11f-4f1f-a8af-360547e28e84.png">


User Story

AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively

Acceptance Criteria

GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
