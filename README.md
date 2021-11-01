![Logo](wireframes/logo.JPG)

# Southern Cross Equestrian Centre



# Goal for this Project
The goal of this project is to design and build a website to advertise an Equestrian Centre and inspire people 
to become customers.

It should provide information about the centre, what it offers, where it is and how to get there.
It should provide various means of contacing the organisers, phone numbers, email and submitting a question or query 
via a form.


![Responsive Displays](wireframes/different-displays.JPG)

# Table of Contents
* [UX](#ux "UX")
    * [User Goals](#user-goals "User Goals")
    * [User Stories](#user-stories "User Stories")
    * [Site Owners Goals](#site-owners-goals)
    * [User Requirements and Expectations](#user-requirements-and-expectations)
         * [Requirements](#requirements)
         * [Expectations](#expectations)
     * [Design Choices](#design-choices)
        * [Fonts](#fonts)
        * [Icons](#icons)
        * [Colours](#colours)
        * [Structure](#structure)
    * [Wireframes](#wireframes)
    * [Features](#features)
        * [Existing Features](#existing-features)
            * [Navigation Bar](#navigation-bar)
            * [Home Page](#home-page)
            * [Gallery Page](#gallery-page)
            * [Contact Us Page](#contact-us-page)
            * [Footer](#footer)
        * [Features to be implemented](#features-to-be-implemented)
    * [Technologies used](#technologies-used)
        * [Languages](#languages)
        * [Tools and Libraries](#tools-and-libraries)
    * [Testing](#testing)
        * [Unfixed Bugs](#unfixed-bugs)
    * [Deployment](#deployment)
    * [Credits](#credits)
# UX

## User Goals
* Visually appealing, including images.
* Easily navigated around.
* Quality and valuable content.
* Easily found contact details.
* Form to directly contact the centre.
## User Stories
* I want to find out where the centre is and what the contact details are.
* I want to submit a question.
* I want to find out if it caters for kids.
* Does it do ride-outs, when and how much does it cost?
* What levels of experiance do they do lessons for, what is the schedule and rates?
* Do they do Pony Camps or League competitions? Is there an associated club?
* Do they take animals in on livery and what is the cost?
* Is it safe? Is it approved by <a href="https://www.aire.ie/">AIRE</a>.
## Site owners Goals
* Promote the centre.
* Increase the number of members.
* Increase rankings on search engines.
### Requirements
* Easy to navigate on various screen sizes.
* Clear information on the services provided.
* Keep the user interested with small bits of information to make them want to engage with the centre.
* Simple methods of contacting the centre.
* Visually inviting so users do not leave.
### Expectations
* I expect to know if a form has been submitted properly and if items are not filled in, to be prompted.
* I expect all links to social media sites to be opened in a new tab.
* I expect all navigation links to work correctly.
* I expect screen size not to affect the quality of the website.
* I expect all information to be correct and accurate.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

## Design Choices

### Fonts
I am using Lato for the main body of text and Oswald for the headings.

### Icons
I have used an icon of a horse on my website from the [Font Awesome library](https://fontawesome.com/ "Font Awesome"). 

### Colours
I used [Colourmind](https://colormind.io/ "colourmind") to help in the selection of my colour scheme. I loaded the logo image for AIRE (Association of Irish Riding Establishments) which I will be including in my site and chose a selection that appealed to me. It has natural colors e.g. greens and a contrasting sandy color for a splash of color. It also has a very light shade which is good on the dark green for text.

See [here](docs/images/ColorPallet.JPG).


### Structure
I will be building my website with a mobile first mindset using the iPhone 5/SE (320px) as the smallest screen size for styling to look good on. The screen size breakpoints that I will be using are from [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap").

| Screen Size | Breakpoint |
| ----------- | ---------- |
| x-small     | <576px     |
| small       | => 576px   |
| medium      | => 768px   |
| large       | => 992px   |
| x-large     | => 1200px  |

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Wireframes
I have used [Balsamic](https://balsamiq.com/wireframes/ "Balsamic") to develop my wireframes for my website. I initially imagined the desktop design making sure I included
all the details I wanted in a pleasant and intuitive way. The initial hero image catches the attention and leads on to further more specific information designed to keep the user reading. I then scaled it down for tablets and phones by reducing image sizes and fonts and moving some information to the next line rather.
There are 3 pages, the home page and then a Gallery page and a Contact Us page. The home page is divided into sections that clearly define its purpose and contain quality information that users will be interested in. Navigation is via the navigation bar and via links to internal anchors on the same page.

The wireframes are below:

### [Home Desktop Wireframe](docs/wireframes/Home-Desktop.png "Home Desktop wireframe")
### [Home Tablet Wireframe](docs/wireframes/Home-Tablet.png "Home Tablet wireframe")
### [Home Phone Wireframe](docs/wireframes/Home-Phone.png "Home Phone wireframe")
### [Gallery Desktop Wireframe](docs/wireframes/Home-Desktop.png "Home Desktop wireframe")
### [Gallery Tablet Wireframe](docs/wireframes/Home-Tablet.png "Home Tablet wireframe")
### [Gallery Phone Wireframe](docs/wireframes/Home-Phone.png "Home Phone wireframe")
### [ContactUs Desktop Wireframe](docs/wireframes/ContactUs-Desktop.png "Home Desktop wireframe")
### [ContactUs Tablet Wireframe](docs/wireframes/ContactUs-Tablet.png "Home Tablet wireframe")
### [ContactUs Phone Wireframe](docs/wireframes/ContactUs-Phone.png "Home Phone wireframe")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Features

## Existing Features

### Navigation Bar

The navigation bar is fully responsive to allow for various screen sizes. It includes links to manover around the site easily and the centre logo which doubles as a link back to the home screen.

+ Desktop (>=992px)
\
&nbsp;
    ![Navigation bar](wireframes/nav-bar-desktop.JPG)
    -   Spanning the full width of the device and with all links (Home, About, Events, Contact) to navigate visible, this gives ease and clear use to the end user.

    -   In order for the user to visably see which of the links they are hovering over there is a bar below the text.

    ![Navigation bar on hover](wireframes/nav-bar-hover.JPG)
    \
    &nbsp;
    -   For the user to know that a link has been clicked there is also a visual aid of the text changing colour.

    ![Navigation bar on focus](wireframes/nav-bar-focus.JPG)
    \
    &nbsp;


+ Small devices (<992px)
\
&nbsp;
    - As the navigation bar would be unuseable in the desktop version on smaller devices, it takes on a hamburger style.

    \
    &nbsp;
![Nav bar on small devices](wireframes/nav-bar-small.JPG)

    - When pressed, it opens up the main menu with all the links available then.

    \
    &nbsp;
![Nav bar on small devices expanded](wireframes/nav-bar-small-expanded.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;
### Landing Page

+ The landing page image
    - The image gives the user instant knowledge of what is involved in the centre, and with added animation draws their eye to the site.
    - The text gives instant information to the user on what the centre is. With the added animation of fading in slightly behind the image, it makes the user keep interest. 
    \
    &nbsp;

    ![Landing Page](wireframes/landing-page.JPG)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;


### Welcome Section

+ The welcome section gives a brief introduction to the user on what the Southern Cross Equestrian Centre is and who is welcome.
    \
    &nbsp;

   
    \
    &nbsp;



\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;



\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Footer

+ The footer contains the social media links related to the equestrian centre and the copyright text. These social links all open in a new tab for ease of use to the user and also, so the user has an ability to easily come back to the equestrian centre's site.
    \
    &nbsp;

    ![Contact Section](wireframes/footer.JPG)
    \
    &nbsp;

+ There is also a hover effect over the links, again to improve user experiance.
    \
    &nbsp;

    ![Contact Section](wireframes/footer-hover.JPG)
    \
    &nbsp;

## Features to be Implemented

?

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Technologies used

## Languages
* [HTML](https://en.wikipedia.org/wiki/HTML "HTML")
* [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

## Libraries & Framework
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
## Tools
* [Gitpod](https://www.gitpod.io/ "Gitpod")
* [Balsamic](https://balsamiq.com/wireframes/ "Balsamic")
* [W3C HTML Validation Service](https://validator.w3.org/ "W3C HTML")
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/ "W3C CSS")
* [Bootstrap](https://getbootstrap.com "Bootstrap")
* [Colourmind](https://colormind.io/ "colourmind")
* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Unsplash](https://unsplash.com/ "Unsplash")
* [Box Shadow Generator](https://html-css-js.com/css/generator/box-shadow/ "html-css-js.com")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Testing

?


\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Deployment

Following writing the code then commiting and pushing to GitHub, this project was deployed using GitHub by the following steps.

+ Navigate to the repository on github and click <strong>Settings</strong>.
+ Then select <strong>Pages</strong> on the side navigation.
+ Select the <strong>None</strong> dropdown, and then click <strong>master</strong>.
+ Click on the <strong>Save</strong> button.
+ Now the website is now live on https://evelynfoy.github.io/southern-cross-equestrian-center/
+ If any changes are required, they can be done, commited and pushed to GitHub and the changes will be updated.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Credits

For code inspiration, help and advice,
* [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin")

\
&nbsp;

For content and style inspiration,
* [carrickminesequestrian.ie](https://www.carrickminesequestrian.ie/ "Carrickmines Equestrian Centre")
* [Brennanstown Riding School](https://www.brennanstownrs.ie/ "Brennanstown Riding School")
* [The Padocks Riding Centre](http://www.paddocks.ie/ "The Padocks Riding Centre")


\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;