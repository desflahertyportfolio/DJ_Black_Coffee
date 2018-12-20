**Project Name: DJ Black Coffee**

I chose to build a website for a well known DJ called 'Black Coffee'. He is a South African DJ, record producer and singer-songwriter.He has released 5 albums to date and won the "Breakthrough DJ of the Year" award at the DJ Awards in Ibiza in 2015. He has a large following on social media but does not have a dedicated website. The creation of a website would promote his music and also increase his exposure on social media as well as providing a method to contact the artist or his management companies.

**UX**

*Strategy:* To create an online presence for the DJ as he currently does not have a dedicated website. There is a presence already on Facebook but this is to generic - a custom site would add value. 

The website would be designed for dance music fans or for dance music promoters who would be interested in finding out more about 'Black Coffee' or booking him for an event as well as his existing fan base.They would need to be able to view and buy his material and find out about tour dates and his activity on social media as well as a method to contact him. 
The site built enables visitors to listen to his latest album as well as providing a link to where they can purchase the album on amazon.co.uk. Visitors can also view a schedule of his upcoming tour dates and link to the respective website to purchase a ticket for these. The site provides links to his social media accounts on Facebook,Instagram and Twitter as well as YouTube videos. Visitors can also sign up to a mailing list and complete a booking request form. Management contact details are also provided.

*User Stories:*
As a dance music fan or promoter I would want to: 
listen to a latest album so that I can then purchase it if I like the music,
read about the DJ to become more interested in him as an artist,
view videos of his live performances so I can decide if I would like to go to his concert,
view his upcoming tour dates and link to a website where I can buy a ticket for a show,
view pictures of the artist to stay updated with his activity,
make a booking request through the website to book the DJ,
view contact information for his management if I work in the press industry or wish to have a direct contact method.

A Mockup for the website was created using the balsamiq software tool. Mockups for the proposed sections can be found in the project folder on github https://github.com/desflaherty/project1/tree/master/MockUp

**Features:**
Index.html - This is the home page for the website that provides links to the different sections in the website located on the navigation bar on the top right of the screen. A logo is used here as a home button. There is also an enquiry button that opens a modal form where a user can input their details for bookings or enquiries.
About.html - A biography section about the DJ and his awards etc.
Index.html#music - An embedded SoundCloud playlist where the user can listen to a sample of his Album in the browser window or link to SoundCloud as well as a link to Amazon.co.uk where the album can be purchased.
Index.html#video - Embedded videos from YouTube of live DJ sets.
Index.html#gallery - A series of photographs that link to the respective photo on his Instagram account.
Index.html#tour -Upcoming tour dates and location as well as links to the websites where tickets can be purchased.
Index.html#contact - Contact information for the DJs management company as well as a sign up form for his newsletter to receive the latest news.

*Existing Features:*
Index.html:
Black Coffee Logo  - which acts as a link to the home page when the user clicks on it.
Navigation Bar - allows users to clearly navigate to the different sections in the website. A underline text effect is implemented on mouse over as well as a fixed underline when the user is on a particular section. The underline effect works in conjuction with the scrollbar using bootstraps scrollspy feature. The underline effect is implemented using a separate css file called underline.css contained in the assets folder.
Nav bar toggle - drop down links for viewing the website on mobile.
A Enquiry button - allows users to completed a form entering their details for a booking or enquiry.
Index.html#music - Embedded SoundCloud playlist & link to amazon.co.uk site where the album 'pieces of me' can be purchased.
Index.html#video - Embedded videos fom YouTube that can be viewed in the browser window of the DJs live performances.
Index.html#gallery - Photos with external links to the respective photos that have been uploaded to by the DJ to his Instagram webpage.
Index.html#tour - Buttons that can be clicked on that will bring the user to the respective webpage where they can purchase tickets for the concerts.
Index.html#contact - A signup input form where the user can enter their e-mail details.
Footer/Social Media Links - Links to the DJ's Instagram, Twitter, YouTube and Facebook accounts.

*Features Left to Implement:*
Future plans could include more video and music content for future releases, a separate news section for articles and press releases, links to soundcloud and itunes beside the social media links. A more advanced collapsed menu for viewing the website on mobile.


**Technologies Used:**
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

*HTML5* -The webs core markup language used for creating content for the web. HTML5 is the 5th edition of the language.       https://www.w3.org/TR/html52/
*CSS* - Used in two files style.css and underline.css. Style.css containes the stylesheet used to format the presentation of the website. The underline.css styelsheet controls the mouse over underline effect for the navigation items in the nav bar. https://www.w3.org/standards/webdesign/htmlcss
*Bootstrap 3.3.7* -An open source toolkit for developing with HTML, CSS and JS https://getbootstrap.com/
*Javascript* -An object-oriented computer programming language commonly used to create interactive effects within web browsers. https://developer.mozilla.org/bm/docs/Web/JavaScript
*Font Awesome* - A font and icon toolkit based on CSS and LESS https://fontawesome.com/
*Google Fonts* -A library of fontsthat can be used in the website https://fonts.google.com/
*JQuery* - A JavaScript library used to simplify DOM manipulation. https://jquery.com/
*Photoshop* -  A Trial version was used to create the Black Coffee Logo used on the site - cropped from a photo sourced online. https://www.photoshop.com
*DownloadGram* - Third party software used to download photos from Instagram for use in the gallery section on the website. https://downloadgram.com/


**Testing**

Both index.html & about.html were checked with HTML validator https://validator.w3.org/#validate_by_input to remove as many warnings as possible, all errors were removed. The CSS style sheet was checked using http://csslint.net/ There were no errors but there are some warning messages returned.

Responsinator was used to check responsiveness of different devices - https://www.responsinator.com as well as google chrome developer.
Devices tested on include: Galaxy S5, iPhone 5/SE, iPhone 6/7/8, iPhone 6/7/8 Plus, iPhone X, iPad, iPad Pro, Desktop PC. Browsers tested were Google Chrome,Internet Explorer and Firefox. Also the Safari browser on iPhone.

*Index.html:*
The 'Enquiry' button was clicked on to ensure it opens and displays a form. When an empty form is submitted an error message is displayed correctly. An invalid email & telephone input displays an error as well as any blank fields not filled in. When the form is correctly populated and submitted a response is correctly displayed.

The nanvigation links work as expected , the hover over generates a red underline effect to enhance the appearance of the links and usability and this line remains on the active link to show the user which section they are on. The underline updates according to the user scroll within the sections on the page. When the link is clicked the user is taken to the respective section. The logo acts a button to take the user to the index.html page.

When viewed in a smaller device such as mobile the navigation menu collapses as expected to become a drop down menu represented by icons in the right of the top right of the screen.

*About.html:*
The text is scrollable and the background image stays in place. Tested on different divices the text is visiable and appears as expected.

*Index.html#Music*
The embedded SoundCloud audio plays as expected when the user clicks the play button. The pause also works. Tested on different devices the embedded music screen is responsive and can be viewed on smaller devices such as mobile. The button to purchase on amazon.co.uk takes the user to an external website on the album page on amazon.

*Index.html#Video*
The embedded Videos play in the browser window and are also responsive, they stack under each other for a smaller device view.

*Index.html#Gallery*
The gallery images are also responsive. There are two rows of 4 images on iPad and desktop , that stack on top of each other for smaller devices. Each image takes the user to the respective external image in Instagram.

*Index.html#Tour*
The tour dates align correctly when viewed on smaller devices. Each ticket button takes the user to the correct external website where they can purchase a ticket for the tour date. The hover over effect on the buttons also works correctly 

*Index.html#Contact*
The signup form works as expected. If the user click on submit with no input an error message will be displayed. A correct email format must be entered and when correctly entered a response is generated when the user clicks the submit button.

*Index.html#Footer*
The social media links work as expected when the user clicks on each button they are taken to an external webpage of the DJ's social media account page. The hover over effect also works correctly the transparent background animates to a red colour when the user mouses over each button. A media query is used to display the social media buttons to the left of the screen on smaller devices as this is more visually appealing.

*Problems/Bugs:*
When tested on iPad there is a small white line appearing under the footer and also between the 'tour' and 'contact' section background images. This only appears when testing on chrome developer but does not show on Internet Explorer using responsinator.
When tested on Galaxy S5 & iPhone not all tour dates are immediately visiable, the user would need to scroll down to view all the dates. Also seen for the 'video' & 'contact' section where vertical scrolling is needed.
When the 'enquiry' button is clicked the modal that opens causes the navbar to move to the right of the screen over the scrollbar, but this re-sets when the enquiry form is closed. This does not show on iPhone 5/SE or Galaxy S5 but can be seen on larger devices iPhone 6/7 and iPad.


*Deployment*
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X

