This is the Assignment 2 project of the course Web Engineering.
Ubaid's Student Registration Form
This is my project for the responsive form assignment. It's a complete, working student registration form built with just HTML5 and CSS3.


How to Run It
It's just a static site, so no server or setup is needed.

Put index.html and styles.css in the same folder.

Open the index.html file in any web browser.


What I Did (Features & Approach)
I focused on hitting all the requirements, especially accessibility and responsive design.


All Form Controls: I made sure to use all the required inputs:

text, date, email, tel, password, radio and checkbox, select with <optgroup>,textarea, file, and datalist.


Responsive Layout: The design is mobile-first.

On screens wider than 768px, a media query kicks in and switches the layout to a two-column CSS Grid.

I used Flexbox for smaller alignments, like the buttons.


Accessibility:

Every single input is connected to a <label> with for and id.


The whole form works perfectly with keyboard navigation. I added a clear :focus-visible style for all inputs, including the custom radio/checkboxes.


CSS:

I used CSS Variables (:root) at the top of the file for all the colours, fonts, and border-radius. This makes it super easy to change the theme.

The custom radio buttons and checkboxes are pure CSS—no images or hacks.
