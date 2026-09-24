APEX AUTO CLUB
=============

A seven-page student website about cars, body styles and club activities.
Assignment #1: HTML & CSS Basics.
Assignment #2: Advanced CSS - Flexbox & Grid.

GETTING STARTED
---------------
Open index.html in a web browser. No installation or build step is required.
Keep all HTML files, the css folder and the images folder together so that
navigation, styles and photographs load correctly.

PAGES
-----
index.html     Home page and introduction to the club.
about.html     Club overview, meeting guidelines and team information.
cars.html      Photo collection cards with notes on vehicle design.
gallery.html   Photo gallery (12 images) with hover captions.   [Assignment #2]
compare.html   Comparison of coupe, sedan and hatchback body styles.
events.html    Proposed club meets and photography sessions.
join.html      Membership enquiry form.

PROJECT STRUCTURE
-----------------
apex-auto-club/
    index.html, about.html, cars.html, gallery.html,
    compare.html, events.html, join.html
    css/
        style.css
    images/
        photographs (JPG), logo.svg, CREDITS.txt
    README.txt

WHAT IS NEW IN ASSIGNMENT #2 (css/style.css)
--------------------------------------------
FLEXBOX
  Navigation bar ....... #main-header, .brand, .nav-menu
  Card row ............. .card-row, .card, .card-body (index, cars, events)
  Small components ..... .profile, .points (comparison), .form-row (join),
                         .sidebar, .footer-inner
GRID
  Page layout .......... .page with grid-template-areas:
                         header / sidebar / main / footer
  Two-column content ... .split (about, events, join)
  Image gallery ........ .gallery (3 columns x 4 rows, gap, hover captions)
RESPONSIVE
  At 900px the page grid becomes one column (header, main, sidebar, footer);
  at 800px the navigation stacks and the card row becomes a column;
  at 480px the gallery becomes one column.

TEAM AND PAGE RESPONSIBILITIES
------------------------------
Baizakov Darkhan   Home and About
Kaldar Serzhan     Cars and Comparison
Tagai Talgar       Events and Join
Shared             Gallery page, css/style.css

EDITING THE WEBSITE
-------------------
Edit the HTML files to change page content. Edit css/style.css to change
colours, typography, spacing and layout across the site.

Navigation, sidebar and footer markup are included in each HTML file. Apply
shared changes to all seven pages to keep them consistent.

FORM BEHAVIOUR
--------------
The membership form is a demonstration. The browser checks required fields
and the email format before displaying a confirmation of the check.
It does not send emails or store enquiries. Submitted values appear in the
page URL, so use sample details when testing.

IMAGE CREDITS
-------------
Photograph authors, source links and licence information are listed in
images/CREDITS.txt.
