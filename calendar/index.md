---
calendar:
  eventSources:
    - events:
      - title: "hello"
        start: 2019-09-07
        end: 2019-09-09
  plugins:
    - dayGrid
  fixedWeekCount: false
  showNonCurrentDates: false
  header: false
  validRange:
    start: 2019-08-29
    end: 2019-12-21
render:
  - selector: "#calendar-august"
    defaultDate: 2019-08-01
  - selector: "#calendar-september"
    defaultDate: 2019-09-01
  - selector: "#calendar-october"
    defaultDate: 2019-10-01
  - selector: "#calendar-november"
    defaultDate: 2019-11-01
  - selector: "#calendar-december"
    defaultDate: 2019-12-01
---

Calendar
========

**🚧  Work in Progress  🚧**

August
------

<div id="calendar-august"></div>

September
---------

<div id="calendar-september"></div>

October
-------

<div id="calendar-october"></div>

November
--------

<div id="calendar-november"></div>

December
--------

<div id="calendar-december"></div>

<script src="fullcalendar-4.2.0/packages/core/main.min.js"></script>
<script src="fullcalendar-4.2.0/packages/daygrid/main.min.js"></script>
<link rel="stylesheet" type="text/css" href="fullcalendar-4.2.0/packages/core/main.min.css">
<link rel="stylesheet" type="text/css" href="fullcalendar-4.2.0/packages/daygrid/main.min.css">
<script>
{{ page.render | jsonify }}.forEach(({ selector, defaultDate }) => {
  new FullCalendar.Calendar(document.querySelector(selector), {
    ...{{ page.calendar | jsonify }},
    defaultDate
  }).render();
});
</script>

* * *

Lectures are held on Wednesdays and Laboratories are held on Mondays.

Individual Assignments start after Lectures on Wednesdays and end in one week.

We recommend that you submit by the Soft Deadline (Wednesdays) to avoid overlaps with the subsequent Assignment, but you may submit until the Hard Deadline (Mondays) without consequences. We don’t accept submissions after the Hard Deadline because by then we already started grading and publishing answers.

Group Project Iterations start on Wednesdays and end in two weeks.

Hard Deadlines for Individual Assignments don’t coincide with the end of Group Project Iterations.

All Deadlines are at 13:15, which is 15 minutes before the class starts. This applies both to Individual Assignments and to Group Project Iterations.

For administrative matters, for example, the last day to drop courses, refer to the [university’s academic calendar](https://studentaffairs.jhu.edu/registrar/wp-content/uploads/sites/23/2017/03/FINAL.academic-calendar-2019-2020.REVISED_4.29.2019.pdf).

2019-08-29 · Thursday
---------------------

👨‍🏫  **Lecture:**

📗  Individual Assignment 0 Start

🛠  Group Project Iteration 0 Start

Though we usually meet on Mondays & Wednesdays, our first day of classes is actually on a Thursday to make up for the holiday on the following Monday (Labor Day).

2019-09-02 · Monday
-------------------

🏭  **No Class:** Labor Day

2019-09-04 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 0 Soft Deadline

📗  Individual Assignment 1 Start

2019-09-09 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 0 Hard Deadline

2019-09-11 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 1 Soft Deadline

📗  Individual Assignment 2 Start

🛠  Group Project Iteration 1 End & Iteration 2 Start

2019-09-16 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 1 Hard Deadline

2019-09-18 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 2 Soft Deadline

📗  Individual Assignment 3 Start

2019-09-23 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 2 Hard Deadline

2019-09-25 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 3 Soft Deadline

📗  Individual Assignment 4 Start

🛠  Group Project Iteration 2 End & Iteration 3 Start

2019-09-30 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 3 Hard Deadline

2019-10-02 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 4 Soft Deadline

📗  Individual Assignment 5 Start

2019-10-07 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 4 Hard Deadline

2019-10-09 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 5 Soft Deadline

📗  Individual Assignment 6 Start

🛠  Group Project Iteration 2 End & Iteration 3 Start

2019-10-14 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 5 Hard Deadline

2019-10-16 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 6 Soft Deadline

📗  Individual Assignment 7 Start

2019-10-21 · Monday
-------------------

🗣  **Overview Presentations**

📕  Individual Assignment 6 Hard Deadline

2019-10-23 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 7 Soft Deadline

📗  Individual Assignment 8 Start

🛠  Group Project Iteration 3 End & Iteration 4 Start

2019-10-28 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 7 Hard Deadline

2019-10-30 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 8 Soft Deadline

📗  Individual Assignment 9 Start

2019-11-04 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 8 Hard Deadline

2019-11-06 · Wednesday
----------------------

👨‍🏫  **Lecture:**

📙  Individual Assignment 9 Soft Deadline

📗  Individual Assignment 10 Start

🛠  Group Project Iteration 4 End & Iteration 5 Start

2019-11-11 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 9 Hard Deadline

2019-11-13 · Wednesday
----------------------

👨‍🏫  **Lecture:** Quiz Review

📙  Individual Assignment 10 Soft Deadline

2019-11-18 · Monday
-------------------

💻  **Laboratory:**

📕  Individual Assignment 10 Hard Deadline

2019-11-20 · Wednesday
----------------------

📝  **Quiz**

🛠  Group Project Iteration 5 End

2019-11-25 · Monday & 2019-11-27 · Wednesday
--------------------------------------------

🦃  **No Class:** Thanksgiving Vacation

2019-12-02 · Monday
-------------------

💻  **Laboratory:**

🛠  Group Project Iteration 6 Start

2019-12-04 · Wednesday
----------------------

💻  **Laboratory:**

2019-12-09 · Monday & 2019-12-11 · Wednesday
--------------------------------------------

📚  **No Class:** Reading Period

2019-12-16 · Monday – 2019-12-18 · Wednesday
--------------------------------------------

🗣  **Final Presentations**

🛠  Group Project Iteration 6 End
