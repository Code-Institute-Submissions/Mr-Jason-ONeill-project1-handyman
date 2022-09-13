# Project1-Handyman
Only using HTML, CSS and Bootstrap
-----------------------------------------------------------------------------
----------------UI---------------
Images will be taken from Unsplash.com and or istockphoto.com 
Background image to cover full background - use opacity to make it a little transparent.
NavBar - #Logo|     ##Link 1 ##Link 2 ##Link 3
Main section - 2* div containers, 1 - Images, 2 - Information
Footer - #Logo |    ##Link 4        ##Link 5        #####Social Links/icons


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

Home page - About the Company and the services they offer.

Job Page - List of jobs that they carry out with prices that they charge. (Possibly add drop down list when user hovers over job page).

Contact page - List of contact information.

Footer - To take users' to external, social media sites.

-----------------SURFACE-------------

Colors - Black, white, grey used in header, footer and background. And yellow or bright color to highlight important/key information.

Fonts- Large, and spacious (Possibly Roboto) - for simplicity and easy to read.

Large images in card form with titles - To help advertise clients work.



-------------------------------------------------------------Bugs & Fixes

Hamburger menu button - not working on small screens. Not including JavaScript, so put nav-links into left & right sections so they're easy to see for all users.
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark container-fluid">
            <span class="navbar-brand"><h1 id="logo">Handyman</h1></span>
            <div class="container">
              <div class="d-flex" id="navbar-menu" style='width: 100%;'>
        
                 <div class="mr-auto" id="navbar-menu-left-side">
                    <ul class="navbar-nav">
                       <li class="nav-item">
                        <a class="nav-link" href="#" aria-current="Home Page">Home<span class="sr-only">Home</span></a>
                      </li>
                      <li class="nav-item">
                        <a class="nav-link" href="jobs.html">Handy Jobs<span class="sr-only">Jobs</span></a>
                      </li>
                    </ul>
                 </div>
        
                 <div id="navbar-menu-right-side">
                    <ul class="nav navbar-nav action-links">
                       <li class="nav-item">
                        <a class="nav-item nav-link" href="contact.html">Contact Us<span class="sr-only">Contact Me</span></a>
                      </li>
                    </ul>
                 </div>

img-cards on the right to be placed under text on smaller screens. Inspecting code, suggests removing = .card-img-top { width:100; } has been removed, still not working. 
Changed layout of website, each section is now in a block style rather than grid, as it is more appealing on each screen size.
    <div class="container-fluid main-section">        
        <div class="row">
          <div class="col col-md-12">
            <div class="job-card">
              <div class="card-header">
                <h3 class="pricing">Lawn Maintenance</h3>
              </div>
              <div class="card-body">
                <h2 class="price-text">£15 / ph</h2>
                <details>Cutting grass, trimming hedges, cutting down small trees &
                  pressure washing patios.</details>
              </div>
            </div>
Footer on contact page, not sitting at the bottom of the page, creating whitespace underneath, code is identical to other pages, not sure of the issue - textarea was not set to specific size causing the footer to raise, and lower if textarea size was changed via the user. Set a size, all okay.
textarea {
  width: 100%;
  height: 350px;
}
