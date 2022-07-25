# 100 Days Of Code - Log

### Day 1: July 16, 2022
**Today's Progress**: Completed Overhaul of Mocside Grade Grid

**Thoughts:** Initially I was attempting to color the problems on page load, but they aren't loaded until expanded, which ultimately meant they were getting no colors. After realizing this I redesigned how and when I colored the problems so that both the labs and the problems of each lab are accurately colored. This took me longer than I thought it should.

**What I Accomplished Today**: 
  * Fixed the sorting of Mocside Coruses, Labs, & Grades
  * Fixed the percent complete and most recent activity for Labs in Mocside
  * Re-enabled the coloring of the labs and problems table rows for complete and incomplete problems
  * Completed the Grade Grid overhaul


### Day 2: July 17, 2022
**Today's Progress**: Started Work overhauling the Course Edit Page

**Thoughts:** CSS is not my strong suite and it shows, this particular overhaul is very css and style heavy. I can handle it no problem but it doesn't come as naturally or as quickly as writing code that performs functions and such.

**What I Accomplished Today**:
 * Began overhaul of Course Edit
 * Moved Key-generation to its own component
 * Fixed the keygen functions after migrating them
 * Split key create and the list of keys into two side by side sections
 * Converted list of keys into a table format and replace the links to copy and delete with font awesome icons

### Day 3: July 18, 2022
**Today's Progress**: Completed the Key-generation styling and Functionality

**Thoughts:** Finished the keygen section, both the styling and the functionality.<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It looks way better than it did, and I'm super happy with it.

**What I Accomplished Today**:
 * Filtered the date in the keygen table so only m/d/y is shown
 * Moved around the key generation methods and inputs
 * made labels smaller to increase focus to the inputs
 * Moved Expire Date and Expire Time to be one line
 * Moved the generation button over

### Day 4: July 19, 2022
**Today's Progress**: Moved Course Roster into its own component

**Thoughts:** Today I handled both funcionality and styling.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Because it was similar to previous styling it went much quicker.

**What I Accomplished Today**:
 * Moved the Roster into a dedicated file
 * Fixed the loading of the student roster after migration
 * Fixed the styling of the grid, student view button, and label

### Day 5: July 20, 2022
**Today's Progress**: course lab list to dedicated component, remove student

**Thoughts:** Today was a functionality and migration day.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Will need to complete function of both pages and lab styling.

**What I Accomplished Today**:
 * Added the ability to remove a student using the course edit roster list
 * moved the course edit lab list to its own component
 * Fixed the loading of the labs after migration

### Day 6: July 21, 2022
**Today's Progress**: Finished the course Lab list

**Thoughts:** Everything went super quickly today both styling and functionality.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I got a lot done in a short amount of time.

**What I Accomplished Today**:
 * Finished styling of the Course Lab List
 * Professor can add a lab from inside course edit
 * Professor can delete a lab from inside course edit
 * Professor can edit a lab from inside course edit
 * Professor can go to a given lab by clicking on it

### Day 7: July 22, 2022
**Today's Progress**: Created a bat+python script to change my background every day

**Thoughts:** Today I decided to write some bat and python scripts.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The script I wrote gets the Astronomy picture of the day,
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and sets that as my background

**What I Accomplished Today**:
 * Wrote a python script to download Nasa's Astronomy Picture of the Day(APOD).
 * Added the ability to set that newly downloaded picture as my desktop background
 * Added a bat script that runs the python script
 * added a login Task to my pc that runs the bat script
 * All together it gives me a cool new Astronomy background every single day

### Day 8: July 23, 2022
**Today's Progress**: Today I moved the final section of course edit

**Thoughts:** Moved the final section into it's own component, fixed styling & function
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Only need to add 2 more functions to the course roster component:
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The ability to add a student, & a student view button

**What I Accomplished Today**:
 * moved the course details section into its own component
 * fixed the functions that broke after migration
 * fixed the styling

### Day 9: July 24, 2022
**Today's Progress**: Added the student view to Labs

**Thoughts:** It could still use a little work, but its functional at the very least.

**What I Accomplished Today**:
 * Added a student view to the labs page.
 * Added functionality to student view button in course edit.
