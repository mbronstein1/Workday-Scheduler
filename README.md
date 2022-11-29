# Workday Scheduler

## Description
This is the fifth challenge in the Northwestern Coding Bootcamp (Module 5). We were required to create a workday calendar that accepted inputs and saved them to local storage, as well as tracking the current time and color-coding the calendar depending on whether the time is past, current, or future. Each input will remain when you refresh as long as you clicked the blue save button on the right until you delete the input manually and click the save button. We were given most of the css but had to figure out where in the html the classes needed to be inputted. We also were given zero js, so that was either built from scratch or imported with momentjs and jquery.

As this module was about third-party APIs, we implemented Bootstrap, jQuery, and moment.js.

## Link to live page
[Live Link](https://mbronstein1.github.io/Workday-Scheduler/)

## Screenshot
![Webpage Screenshot](./assets/images/Work-day-scheduler-screenshot.jpg)

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```md
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```