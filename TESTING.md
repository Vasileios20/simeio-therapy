# Simeio Therapy - Testing

![mock up image](documentation/features-img/mock-up.png)

View the deployed site [Simeio Therapy](https://vasileios20.github.io/simeio-therapy/index.html)

The project has been tested in the following browsers Google Chrome, Firefox, Safari and Opera.

# Contents 

* [Automated Testing](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
    * [Lighthouse Desktop](#lighthouse-desktop)
    * [Lighthouse Mobile](#lighthouse-mobile)
  * [WAVE](#wave)
* [Manual Testing](#manual-testing)
* [Bugs](#bugs)
  * [Solved Bugs](#solved-bugs)

W3C Validator have been used to check the HMTL & CSS.

Google Developer tools have been used through the developement of the project to address any style issues and to test responsiveness in various sceen sizes.

WAVE have been used to test the accessibility of the site.

## Automated Testing
### W3C Validator

* [index.html](documentation/testing/w3c/w3c-index.png)
* [about-us.html](documentation/tessting/w3c/w3c-about-us.png)
* [cv-maria.html](documentation/testing/w3c/w3c-cv-maria.png)
* [cv-gelly.html](documentation/testing/w3c/w3c-cv-gelly.png)
* [cv-elena.html](documentation/testing/w3c/w3c-cv-elena.png)
* [cv-katerina.html](documentation/testing/w3c/w3c-cv-katerina.png)
* [speech-therapy.html](documentation/testing/w3c/w3c-speech-therapy.png)
* [occupational-therapy.html](documentation/testing/w3c/w3c-occcupational-therapy.png)
* [parental-counselling.html](documentation/testing/w3c/w3c-parental-counselling.png)
* [special-education.html](documentation/testing/w3c/w3c-parental-counselling.png)
* [contact.html](documentation/testing/w3c/w3c-contact.png)
* [thank-you.html](documentation/testing/w3c/w3c-thank-you-pg.png)
* [404.html](documentation/testing/w3c/w3-404.png)
* [style.css](documentation/testing/w3c/w3c-style.png)

### Lighthouse 

Lighthouse, within the Chrome Developer Tools, have been used to test the performance, accessibility, best practices and SEO of the website both on desktop and mobile.

SEO on all pages is 90-92, that is because to create the hamburger menu I had to add a checkbox input, without an href as on mobile devices wouldn't open the menu. [Borrowed code for the hamburger menu](https://codepen.io/alvarotrigo/pen/MWEJEWG)

#### Lighthouse Desktop
* [index.html](documentation/testing/lighthouse/index.png)
* [about-us.html](documentation/testing/lighthouse/about-us.png)
* [cv-maria.html](documentation/testing/lighthouse/cv-maria.png)
* [cv-gelly.html](documentation/testing/lighthouse/cv-gelly.png)
* [cv-elena.html](documentation/testing/lighthouse/cv-elena.png)
* [cv-katerina.html](documentation/testing/lighthouse/cv-katerina.png)
* [speech-therapy.html](documentation/testing/lighthouse/speech-therapy.png)
* [occupational-therapy.html](documentation/testing/lighthouse/occupational-therapy.png)
* [parental-counselling.html](documentation/testing/lighthouse/parental-counselling.png)
* [special-education.html](documentation/testing/lighthouse/special-education.png)
* [contact.html](documentation/testing/lighthouse/contact.png)
* [thank-you.html](documentation/testing/lighthouse/thank-you.png)

#### Lighthouse Mobile

* [index.html](documentation/testing/lighthouse/index-mobile.png)
* [about-us.html](documentation/testing/lighthouse/about-us-mobile.png)
* [cv-maria.html](documentation/testing/lighthouse/cv-maria-mobile.png)
* [cv-gelly.html](documentation/testing/lighthouse/cv-gelly-mobile.png)
* [cv-elena.html](documentation/testing/lighthouse/cv-elena-mobile.png)
* [cv-katerina.html](documentation/testing/lighthouse/cv-katerina-mobile.png)
* [speech-therapy.html](documentation/testing/lighthouse/speech-therapy-mobile.png)
* [occupational-therapy.html](documentation/testing/lighthouse/occupational-therapy-mobile.png)
* [parental-counselling.html](documentation/testing/lighthouse/parental-counselling-mobile.png)
* [special-education.html](documentation/testing/lighthouse/special-education-mobile.png)
* [contact.html](documentation/testing/lighthouse/contact-mobile.png)
* [thank-you.html](documentation/testing/lighthouse/thank-you-mobile.png)


### WAVE

Each page was run through the Web Accessibility Evalulation Tool (WAVE).

The alerts on all pages come from the hamburger menu where I had to add a checkbox input, without an href as on mobile devices wouldn't open the menu. [Borrowed code for the hamburger menu](https://codepen.io/alvarotrigo/pen/MWEJEWG)

On 404 page the alerts come from the text content that the tool (WAVE) considers as headings.

* [index.html](documentation/testing/wave/index.png)
* [about-us.html](documentation/testing/wave/about-us.png)
* [cv-maria.html](documentation/testing/wave/cv-maria.png)
* [cv-gelly.html](documentation/testing/wave/cv-gelly.png)
* [cv-elena.html](documentation/testing/wave/cv-elena.png)
* [cv-katerina.html](documentation/testing/wave/cv-katerina.png)
* [speech-therapy.html](documentation/testing/wave/speech-therapy.png)
* [occupational-therapy.html](documentation/testing/wave/occupational-therapy.png)
* [parental-counselling.html](documentation/testing/wave/parental-counselling.png)
* [special-education.html](documentation/testing/wave/special-education.png)
* [contact.html](documentation/testing/wave/contact.png)
* [thank-you.html](documentation/testing/wave/thank-you.png)
* [404.html](documentation/testing/wave/404.png)

## Manual Testing

Testing was performed on the following devices :

OnePlus 8T, OnePlus Nord 2, Toshiba Portege Z30 13.3", Desktop PC Windows, Samsung SmartTV 4K.

One of the owners of Special Treatments Center "simeio" tested on iPad 4, iPhone 11, Mac mini 1.

Friends and family has perfomed tests in various mobile devices and reported no issues.

|Feature|Expected Outcome|Testing Performed|Result|Pass/Fail|
|--|--|--|--|--|
|Navbar (Test on all pages)|
|Logo Image link|Redirect to home page|Clicked Logo|Redirected to home page|Pass|
|About Us|Redirect to about us page|Clicked button|Redirected to about us page|Pass|
|Contact|Redirect to contact page|Clicked button|Redirected to contact page|Pass|
|Services|On hover show dropdown menu|Hovered with mouse|Dropdown menu shown|Pass|
|Dropdown Menu|On hover coloured background to dropdown menu buttons|Hovered with mouse|Coloured background buttons|Pass|
|Services Dropdown Menu Speech Therapy button|Redirect to speech therapy page|Clicked button|Redirect to speech therapy page|Pass|
|Services Dropdown Menu Occupational Therapy button|Redirect to occupational therapy page|Clicked button|Redirected to occupational therapy page|Pass|
|Services Dropdown Menu Parental Counselling button|Redirect to parental counselling page|Clicked button|Redirected to parental counselling page|Pass|
|Services Dropdown Menu Special Education button|Redirect to special education page|Clicked button|Redirected to special education page|Pass|
|Home Page (Desktop and Mobile)|
|Speech Therapy button "Learn more about this service"|Redirect to speech therapy page|Clicked button|Redirect to speech therapy page|Pass|
|Occupational Therapy button "Learn more about this service"|Redirect to occupational therapy page|Clicked button|Redirected to occupational therapy page|Pass|
|Parental Counselling button "Learn more about this service"|Redirect to parental counselling page|Clicked button|Redirected to parental counselling page|Pass|
|Special Education button "Learn more about this service"|Redirect to special education page|Clicked button|Redirected to special education page|Pass|
|About Us Page (Desktop and Mobile)|
|Card Maria "view profile" button|Redirect to cv-maria page|Clicked button|Redirected to cv-maria page|Pass|
|Card Aggeliki "view profile" button|Redirect to cv-gelly page|Clicked button|Redirected to cv-grlly page|Pass|
|Card Elena "view profile" button|Redirect to cv-elena page|Clicked button|Redirected to cv-elena page|Pass|
|Card Katerina "view profile" button|Redirect to cv-katerina page|Clicked button|Redirected to cv-katerina page|Pass|
|Contact Us Page(Desktop and Mobile)|
|Required fields|When submit the form if empty field show message "Please fill out this field"|Submit form with at least one empty field|Message shown|Pass|
|Email Address Input|When fill out this field accept only email address|Entered non email address and submitted form|Message shown to fill out this field with an email address|Pass|
|Submit button|When submit form redirect to thank you page|Form submitted|Redirected to thank you page|Pass|
|Thank You Page (Desktop and Mobile)|
|Logo Image button at the center of the screen|Redirect to home page|Clicked button|Redirected to home page|Pass|
|404-Error Page (Desktop and Mobile)|
|Logo Image button at the center of the screen|Redirect to home page|Clicked button|Redirected to home page|Pass|
|Mobile device hamburger menu|
|Hamburger menu|On click opens navbar menu|Clicked button|Opened navbar menu|Pass|
|Hamburger menu/About Us|Redirect to about us page|Clicked button|Redirected to about us page|Pass|
|Hamburger menu/Contact|Redirect to contact page|Clicked button|Redirected to contact page|Pass|
|Hamburger menu/Services Dropdown Menu Speech Therapy button|Redirect to speech therapy page|Clicked button|Redirect to speech therapy page|Pass|
|Hamburger menu/Services Dropdown Menu Occupational Therapy button|Redirect to occupational therapy page|Clicked button|Redirected to occupational therapy page|Pass|
|Hamburger menu/Services Dropdown Menu Parental Counselling button|Redirect to parental counselling page|Clicked button|Redirected to parental counselling page|Pass|
|Hamburger menu/Services Dropdown Menu Special Education button|Redirect to special education page|Clicked button|Redirected to special education page|Pass|

## BUGS

### Solved Bugs

|#|Bug|Solution|
|--|--|--|
|1|When I added the logo image to the cv-cards in about-us.html the image wouldn't load| I had to change the path and remove the forward slash from the link, see [commit](https://github.com/Vasileios20/simeio-therapy/commit/e0edc5ffa3db7f6452bb008ad00376dd9c56b6de)|
|2|When I was trying to open the dropdown menu in screens 800px and down (in the hamburger menu) it would load the page again instead of just opening the dropdown menu| I had to add the # symbol to the href attribute for the services button on the navbar, see [commit](https://github.com/Vasileios20/simeio-therapy/commit/89ffcd6d6ac152ebbe4808cd0ac7c0a65de3b874)|
|3|When I added the hamburger menu, on the contact.html, it would be shown be hind the contact form|I had to add z-index to header, see [commit](https://github.com/Vasileios20/simeio-therapy/commit/eed889df1895aa4213115369fdbfefcfb53d6c3b), thank you [Kera](https://github.com/kera-cudmore) for guidance|