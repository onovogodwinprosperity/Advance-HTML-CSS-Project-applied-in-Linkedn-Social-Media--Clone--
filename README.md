## HTML/CSS used in (Linkdn-clone)  code breakdown and explain :+1:
 # DEMO
 ![Capture 222](https://github.com/onovogodwinprosperity/Advance-HTML-CSS-Project-Linkedn-Social-Media--Clone-/assets/104012600/b3932970-47ec-424d-80ef-80bb4c6a57b5)

# INDEX.HTML BREAKDOWN

Document Type Declaration:
<!DOCTYPE html> specifies that the document is an HTML5 document.

HTML Element:
<html lang="en"> represents the root element of the HTML document. The lang attribute specifies the language of the document.

Head Element:
<head> contains meta-information about the document, such as character encoding, viewport settings, title, and linked stylesheets.

Meta Elements:

<meta charset="UTF-8">: Specifies the character encoding of the document as UTF-8, which supports a wide range of characters from various languages.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Sets the compatibility mode for Internet Explorer.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Specifies the viewport settings for responsive design on different devices.
Title Element:
<title> specifies the title of the web page, which will be displayed in the browser's title bar or tab.

Link Element:
<link rel="stylesheet" href="style.css"> links an external CSS file named "style.css" to the HTML document. This file contains styling information for the website.

Body Element:
<body> contains the visible content of the web page.

Navigation Section:
<nav class="nav"> represents the navigation section of the website. It contains a logo, search box, and a list of navigation links.

Profile Dropdown Menu:
The code defines a profile dropdown menu with a user's profile information, feedback, settings, and other options.

Main Content Section:
<div class="container"> represents the main content area of the website. It contains posts and other content.

Left Sidebar:
<div class="left-sidebar"> contains a user's profile information, activity links, and other related content.

Main Content Section:
<div class="main-content"> contains individual posts and their associated content.

Right Sidebar:
<div class="right-sidebar"> contains trending news, advertisements, useful links, and copyright information.

JavaScript:
The code includes two JavaScript functions that handle toggling the profile dropdown menu and showing/hiding activity links.

These are the main code structures found in the provided HTML document. The website's appearance and functionality are defined through the combination of HTML, CSS, and JavaScript. The CSS file referenced by the link element is likely responsible for styling the elements on the page, while JavaScript functions add interactivity to the dropdown menu and the show/hide behavior of the activity links.

# PROFILE.HTML BREACKDOWN

## DEMO 
![Capture 22222](https://github.com/onovogodwinprosperity/Advance-HTML-CSS-Project-Linkedn-Social-Media--Clone-/assets/104012600/6c99ee2d-460c-4e1c-a59e-fe21094d6bc5)

![21233](https://github.com/onovogodwinprosperity/Advance-HTML-CSS-Project-Linkedn-Social-Media--Clone-/assets/104012600/927e6437-9458-4f2a-bc71-279ab0798ee4)


Document Type Declaration:
<!DOCTYPE html> specifies that the document is an HTML5 document.

HTML Element:
<html lang="en"> represents the root element of the HTML document. The lang attribute specifies the language of the document.

Head Element:
<head> contains meta-information about the document, such as character encoding, viewport settings, title, and linked stylesheets.

Meta Elements:

<meta charset="UTF-8">: Specifies the character encoding of the document as UTF-8, which supports a wide range of characters from various languages.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Sets the compatibility mode for Internet Explorer.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Specifies the viewport settings for responsive design on different devices.
Title Element:
<title> specifies the title of the web page, which will be displayed in the browser's title bar or tab.

Link Element:
<link rel="stylesheet" href="style.css"> links an external CSS file named "style.css" to the HTML document. This file contains styling information for the website.

Body Element:
<body> contains the visible content of the web page.

Navigation Section:
<nav class="nav"> represents the navigation section of the website. It contains a logo, search box, and a list of navigation links.

Profile Dropdown Menu:
The code defines a profile dropdown menu with a user's profile information, feedback, settings, and other options.

Main Content Section:
<div class="container"> represents the main content area of the website. It contains a user's profile information, experiences, education, skills, and other related content.

Profile Sidebar:
<div class="profile-sidebar"> contains advertisements and a list of people that the user may know on the social media platform.

Profile Footer:
<div class="profile-footer"> contains useful links related to the website.

JavaScript:
The code includes a JavaScript function that handles toggling the profile dropdown menu.

These are the main code structures found in the provided HTML document. The website's appearance and functionality are defined through the combination of HTML, CSS, and JavaScript. The CSS file referenced by the link element is likely responsible for styling the elements on the page, while the JavaScript function adds interactivity to the profile dropdown menu.

# CSS BREACKDOwN
*: Applies the following styles to all elements on the page:

margin: 0: Sets the margin to 0 for all elements.
padding: 0: Sets the padding to 0 for all elements.
font-family: 'Poppins', sans-serif;: Sets the font family to 'Poppins' and uses a fallback sans-serif font for all elements.
box-sizing: border-box;: Ensures that padding and border are included in the element's total width and height.
.nav: Styles the navigation bar at the top of the page:

Sets the background color to white.
Adds padding to the top and bottom of the navigation bar.
Sets the navigation bar to stick to the top of the page when scrolling (position: sticky).
Applies a box shadow to give it a subtle shadow effect.
.navbar-center ul li a: Styles the links in the navigation bar:

Adds padding and margin to the links.
Makes the links display as flex containers with centered alignment.
Sets the font size and color for the links.
Adds a pseudo-element (::after) to create an underline effect that grows from the left when the links are hovered or active.
.nav-profile-img: Styles the profile image in the navigation bar:

Sets the width and border radius to create a circular profile image.
Adds a pointer cursor to indicate it is clickable.
.search-box: Styles the search box in the navigation bar:

Sets the background color and width of the search box.
Adds padding to the search box to create spacing between the icon and input field.
Media Query (@media): The styles within the media query are applied only when the screen width is 600 pixels or less (small screen sizes):

Adjusts the layout for smaller screens, such as collapsing the search box and removing some elements from the navigation bar to optimize for mobile devices.
These CSS styles contribute to creating a responsive and visually appealing social media website design
