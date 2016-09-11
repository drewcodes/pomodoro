# pomodoro clock

This project is built around the "pomodoro clock" concept that helps increases productivity by intelligently managing time working and taking breaks. The idea that a user can be productive for 25 minutes and break for 5 minutes relieves the user from being fatigued and wanting to stray from their tasks.

-The clock loads a 25 minute timer by default. A 5 minute break timer is also set.
-Easy to navigate buttons allows users to increment or decrement the timers by 5 minutes at a time. The shortest of both clocks being 5 minutes, with no maximum time limit.
-The clock will exhibit a pop-up alert when either timer has completed. A reset button is then presented to the user to restart the timers.

HTML:
Built using a regular HTML boilerplate. The structure features a few divs as placeholders for the content to be displayed. All colors and styling can be found in the CSS file.

CSS:
All stylings are found within this file. The CSS also contains the class changes for the clock to transform into a different color and background when started. It is triggered by the 'start' button in the JS file.

JavaScript:
All activity on the HTML is built into this JS file. The clock loads with several hidden elements on the page, including the reset button and the different timer descriptions. When started, the clock will reveal the hidden elements and hide unnecessary elements to focus solely on the timer's countdown. The clock is built using the setInterval() method, decrementing per 1000ms. Once the clock reaches 0, it will automatically run the next set of code to begin the break timer. Once the break timer completes, the reset button will show and allow the user to reset the clock.
