DIRECTIONS

1. Create a folder in your main projects folder called "course-project"

2. In that root folder called "course-project," create 6 html files with the following names:
-about.html
-admin.html
-create.html
-index.html
-login.html
-update.html

3. Find the starter files in the Moodle resources for this assignment. Download the "starter-files" folder to your computer. Inside the "starter-files" folder, you'll find mockups for the six HTML pages that are part of the project and a folder called "public".  Inside the "public" folder, there's a folder called "images," and inside the "images" folder, you'll find all the images you need to complete this assignment. 

4. Move the "public" folder into to the "course-project" folder.

5. Use the mockups included in the "starter-files" folder to create the six webpages. Use the hints below to help you with specific pages.

6. Upload your "course-project" folder to a new repo in Github and submit the URL into the assignment on Moodle.


GENERAL HINTS

-Utilize the target="_blank" and the rel="noopener noreferrer" attributes for links that take users to a new website. Find out more here: https://www.w3schools.com/tags/att_a_target.asp and here: https://perishablepress.com/fix-blank-target-vulnerability/ 

-Use the attribute href="#" in any links that you don't want to navigate somewhere else. The pound sign just tells the computer to stay at the current location instead of navigating somewhere else. Find out more here: https://stackoverflow.com/questions/4855168/what-is-href-and-why-is-it-used


NAVBAR AND FOOTER

-Perfect the navbar and footer on one page, and then just copy and paste the code onto the other 5 pages. This will greatly reduce the time it takes you to code these pages. 

--The navbar consists of the CodeSquad Comics logo and the bulleted list of the three navigation links directly below. 

--The footer consists of the "VISIT US" header and everything below it.

-The logo in the footer should link to http://codesquad.org/, and this should open in a new tab in the browser.

-The logo in the navbar should link to the index.html page, and this should not open in a new tab in the browser.

-The links under the "FOLLOW US" header in the footer can link to your personal social media pages or you can make the href attribute equal to "#" to keep the user on the same page when the link is clicked.


INDEX PAGE

-Put the attribute style="width: 200px;" on all the comic book cover images to make them smaller. (You will eventually take this out and style the images with CSS, but adding in the attribute at this step in the design will help make your page easier to view in this first version.)

-All book cover images should also be links, but utilize the href="#" because they won't link anywhere specific until later versions of this project. 

-Also utilize the href="#" for each "Details" link under each comic's title, author, and rating. Eventually these will link to a "Details" page for each comic, but that comes in a later version. 

-TEXT NEEDED FOR THIS PAGE: CodeSquad Comics is a collection of graphic novels read by Your Name. The site is intended to display comic book covers along with information about each book, including the author, a rating, and other details about the graphic novel. Browse through the complete collection below. Click on the cover image or the Details link to see even more information for each graphic novel including the publisher, genre, number of pages, and a brief synopsis. The About page includes meta information about this collection. Login is only available to the site administrator at this time.


ABOUT PAGE

-TEXT NEEDED FOR THIS PAGE: CodeSquad Comics is a collection of graphic novels read by YOUR NAME. Copyrighted images are used for review purposes only. Meta information about this collection can be found below. A detailed list of all the graphic novels in this collection can be found on the homepage. Additional details about each comic book, including the author, genre, number of pages, and a brief synopsis, can be found by navigating to the homepage and clicking the image of the book cover or the Details link for the desired graphic novel.


ADMIN PAGE
-The content on this page is contained in a table. 

LOGIN PAGE, UPDATE PAGE, & CREATE PAGE
-Each of these pages contains a form. Use the action="#" attribute on the opening form tag for now. We won't do anything with the form submission until a much later version of the course project.

-Each label for the input should have a "for" attribute that matches the "id" and "name" attributes in the corresponding input tag. These may not make any sense until we start working with databases later in the course, but they are needed in every form input, so it's a good idea to get in the habit of including them now. 

-Many inputs utilize the "placeholder" attribute. Find more information in our class slides and/or https://www.w3schools.com/html/html_form_attributes.asp 

-For the select inputs on the Create page and the Update page, the possible options are:
--BOOM! Box
--DC Comics
--Harry N. Abrams
--Icon Books
--Image Comics
--Marvel
--Simon & Schuster
--Top Shelf Productions
--VIZ Media LLC

-The form inputs on the Update page are pre-filled with the following values: 
--"title value stored in database"
--"author value stored in database"
--"publisher value stored in database"
--"genre data stored in database"
--"255"
--"5"
--"synopsis value stored in database"

BONUS: Use the "value" attribute for form inputs on the Update page to pre-populate an answer. Learn more about the value attribute here: https://www.w3schools.com/tags/att_value.asp

BONUS: For the select inputs, utilize the "selected" and "disabled" attributes to make it look exactly like the mockups that show the dropdowns. Learn about the "selected" attribute here: https://www.w3schools.com/tags/att_option_selected.asp. Learn about the "disabled" and other form attributes here: https://www.w3schools.com/html/html_form_attributes.asp 


