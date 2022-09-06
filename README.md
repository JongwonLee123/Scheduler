# Scheduler
In this scheduler, I implemented an index.html, script.js, and style.css to produce a editable daily schedule. Tried to match the demo as much as possible.

# Index
In the index, I utilized bootstrap elements by linking a link to a bootstrap link. From there, I began using the classes in the bootstrap code to create a basic outline for the times in the schedule. For each time, I created the same format to make any necessary changes. For each section, I first created a specific id for the time in order to recall any changes made in the local storage. Then, I used columns to stack each of the items on top of another. At the end, I incorporated a button with a special icon from the font link. 

# Style
Nothing was changed in the given script except adding a notification and show class to display changes made to the local storage. The .notification was hidden and formated and the .show was used to create the display to be in a block.\

# Script
When the save button was clicked on, the value and time was collected and stored at the certain time. Then the notification would pop up for a few seconds and then disappear. The hourUpdater was used to check if the time has already passed. If it did, it would mark it as past and turned grey. If it is happenning, it would be marked red. If it is in the future, it would be marked green. For each hour, we recall any values stored in the localStorage and display it in the textArea. The currentDay was called through using moment().format('dddd, MMMM, Do').