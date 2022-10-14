# Barcade

This website has been created for a Bar and Arcade hybrid. The initial page you land on gives
a title, logo and welcome message followed by a description of what to expect from the business.
the business offers a meeting point for people to meet up, socialize, have drinks and play retro gaming
consoles.

The website allows a user to understand the company and have a look at what events are occuring in the coming months.
The website also allows users to make a reservation, view the gallery and see the drinks menu. It also enables users
access to the relevant social media websites.




## Features

### Navigation

- Navigation bar allows users to easily manouvre the various pages of the website
- Logo in top left hand side of the screen can be clicked at any point, on any of the pages on the website in order to return the user to the index page
- All other navigation is in the top right hand corner and allows the user to go to the Menu, Reservation page and the Gallery
- All navigation elements match the color scheme of the website with each word clearly enhanced in white font with a black background
- All navigation elements are clear and to the point, all for easy access to all elements of the website

![Sample images of website in different sizes, phone, laptop, desktop](../projectOne/assets/images/amIResponsive.jpg "Website in different sizes")

### Menu

- The menu style is consistent with the index page, provides the user with a menu outlining options and prices
- The menu is purposely simple, there are 6 options so the user can quickly understand what is available, the font is consistent, white has been used with a parchment style background
- All information is clear and concise

### Reservation

- Reservation page follows same theme as all other elements, has a black background, white font with the form enhanced by implementing a background image of a controller
- The form is simple with no superfluous additions, First name, Last name, reservation date and party size is all that is requested to make a booking
- Black button with white font is used to remain consistent with styling choice throughout the website

### Gallery

- Gallery provides a page to show clients enjoying the arcade and to show off what the premises looks like and what is on offer, this will assist users to decide if this is the destination for what they are looking for


## Testing

- I cascaded the website link to family members and colleagues to test on different devices, used feedback to make relevant changes, mainly media query based fixes on the back of feedback
- I utilised  development tools in order to test the responsiveness of the site, I tested and confirmed each page operates as required for standard screen sizes available
- I tested all clickable links attached to the website, confirmed logo brought user back to home page on each page, confirmed each navigation element operated as required and also confirmed all footer elements lead to the expected social media landing page
- I have tested the form element, I have confirmed that in order to make a reservation, all fields must be filled with the relevant content type. When the form is submitted the values get sent to a confirmation page.


## Bugs

1. Stylesheet was not connecting during early development when using <link rel="stylesheet" href="../ProjectOne/assets/css/style.css">, changed to various types of pathway. Used /assets/css/style.css and this fixed the issue.
2. Added code from stack overflow to set HTML and body to 0 to remove pre set white space.
3. Could not manage to center text for header on gallery page, referred to various forums, used clear:both function to achieve intended result.
4. Was having issues levelling gallery photos during development, gallery sizing not working, used min height and max height to level out pictures.
5. Had an issue where elements that were using the 'display: inline-block' element were not aligning properly, used info from stack overflow to rectify this issue with 'vertical-align: top'. This was the belowDesc section of the website.
6. Had issues where h3 elements were being targetted by preset styling, rectified by targetting h3 elements specifically in each media query
7. links to images and spreadsheet not working after commitment to site, changed spreadsheet link and image links to suit change. For live website ../projectOne/assets/css/style.css is the syntax being used however when using Python server /assets/css/style.css is being used


## Authors

- https://github.com/john33mcd


## Screenshots

![App Screenshot]


## Feedback

If you have any feedback, please reach out to me at jmcd-34@hotmail.com

## Appendix

Any additional information goes here



# Credits

- Utilised readme.so in order to develop read me file, https://readme.so/