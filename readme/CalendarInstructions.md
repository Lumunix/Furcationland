# How to use the Calendar for Events Scheduling

This guide covers add new events to the Bootstrap Caldender present in the Furcationland theme.


## Configuring calendar options

The configuration options for the calendar are inside the file **calendar.md** all calendar options are listed below.

```markdown
---

layout: calendar # do not change
title: Calendar # Title of the page

calendar_timezone_offset: 0000   # enter the timezone as an numerical offset from GMT
calendar_csv: events.csv  # filepath to (CSV) comma separated value that contains the events schedule

calendar_focus_date: 2022-06-25   # default date for calendar to look at when loaded up
calendar_caption: Furcationland Events Schedule   # page caption title

---
```

## Filling calendar with events

The events calendar can be populated by creating a (CSV) with the following table format.
* Note that the csv has to be place in the root directory of the site prior to running Jekyll.



| Title        | Start           | End  |Mark  |URL  |
| ------------- |:-------------:| -----:|-----:|-----:|
| Name of the event      | event start time (GMT) | event end time (GMT) |Event Category Color |Link |


- Title - Name of the event that shows up in the calendar.
- Start - Start time of event in (GMT) time, see the Configuring calendar options section for setting timezone.
- End - Start time of event in (GMT) time, see the Configuring calendar options section for setting timezone.
- Mark - Event category (Under construction, will allow color selection)
- URL - Web link to page on site for specific event.
