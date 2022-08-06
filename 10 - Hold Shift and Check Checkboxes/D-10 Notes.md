### Day 10 | 08.06.22

#### Requirement
The following is a common layout you would see in an email client.

When a user clicks a checkbox, holds Shift, and then clicks another checkbox a few rows down, all the checkboxes inbetween those two checkboxes should be checked.

#### Notes
everytime a checkbox is clicked, inBetween will be set as false by default. next it will check if the actions: shift key is hold + checkbox is checked, are both true. If true, each checkbox input fields will be looped over. 

If the iterated checkbox is the one that was checked along w/ shift or it's the previously checked input field, inBetween will be negated. the value of inBetween flag variable will only change by the two set conditions. 

If inBetween is true, checkboxes input fields will be checked, else it'll be skipped.

To understand more what's happening you can run the site and open the console log

