# Project1-Handyman
Only using HTML, CSS and Bootstrap
-----------------------------------------------------------------------------
----------------UI---------------
Images will be taken from Unsplash.com and or istockphoto.com 

-----------------STRATEGY-------------
Target Audience? - The website will be designed and created for a small start-up business looking to expand their reach.

Who are we aiming this site at? - The elderly, single parents and or the people that are too busy to do the outdoor tasks.

Why would the user want this? - Simple design, easy to locate information they would require.


-----------------SCOPE---------------
User wants? - A website that details what they offer, with a lot of photos to make it look appealing.

User needs? - A website that is easy to navigate and straight to the point.

User needs that they're unaware of? - A payment section.


-----------------STRUCTURE-------------

Navbar along top of website - #H1 - used for Logo/Company name, ##H2 with spacing/padding - used for nav-links (easy to read and navigate between pages). 

Footer layout to match Navbar - include icons for external social media sites - add spacing/padding around each icon.

Main section - split into grid style, one side to contain information other to display images.

-----------------SKELETON-------------

Home page - About the Company and the surfaces they offer.

Job Page - List of jobs that they carry out with prices that they charge. (Possibly add drop down list when user hovers over job page).

Contact page - List of contact information.

Footer - To take users' to external, social media sites.

-----------------SURFACE-------------

Colors - Black, white, grey used in header, footer and background. And yellow or bright color to highlight important/key information.

Fonts- Large, and spacious (Possibly Roboto) - for simplicity and easy to read.

Large images - To help advertise clients work.



-------------------------------------------------------------Bugs & Fixes

Hamburger menu button - not working on small screens. Not including JavaScript, so put nav-links into left & right sections so they're easy to see for all users.

img-cards on the right to be placed under text on smaller screens. Inspecting code, suggests removing = .card-img-top { width:100; } has been removed, still not working. 
Changed layout of website, each section is now in a block style rather than grid, as it is more appealing on each screen size.

Footer on contact page, not sitting at the bottom of the page, creating whitespace underneath, code is identical to other pages, not sure of the issue - textarea was not set to specific size causing the footer to raise, and lower if textarea size was changed via the user. Set a size, all okay.