# **Studio dancers**

Studio dancers wants to spred the joy of dancing! By offering dance classes in several different styles with high class instructors for young adults, the Studio Dancers site hopes to get more young people to stay active by discovering and stay in the amazing world of dance! It is targeted towards those how wants to start dancing and those who already love to dance to make them want to keep dancing! The site is useful for those who want to take a dance class, get information about which classes are offered, where and when they are held, price, etc. and register for a class.

![Studio dancers website showed in different screen sizes provided by https://ui.dev/amiresponsive](documentation/readme-intro.png)

You can find the site [here.]( ADD LINK!!!!! )

## **Features**
---

### **Features relevant to all pages**

#### **Header**

Contains the logo and navigation bar and is located at the top of every page where the user would expect them to be. The logo and navigation bar together give the user the name of the site and where different information can be found. The header provides links to all pages of the site to easily navigate between them. The logo is a link to the home page and the navigation bar links to the other pages; Classes and Sign up.  

The links turn pink or blue when hovering over them, indicating to the user that the object is clickable. 

![Logo and navigation bar](documentation/readme-logo-nav.png)

#### **Footer**

The footer is located at the bottom of every page. It contains icons with links to external social media pages which is useful to the user in order to get even more interesting information about what Studio dancers offers. It has therefore been given a bright blue color to make it stand out from background color of the rest of the site, to be easily found and to not be forgotten.

The links are opened in a new tab, so that the user can stay on the Studio dancers site. 

![Footer](documentation/readme-footer.png)

### **The Home page**

#### **The Introduction section**

This section aims to give the user a warm welcome and is useful to the users as it gives them a first glance of what dancing at Studio dancers could look like. It aims to make them interested and to make them want to continue exploring the page. This is done with a happy image and inspirational and selling words. Words that I want the user to focus on are highlighted with pink and blue color. 

The image has been placed to the left to make it appear directly under the logo and navigation bar on smaller screens.  

![Introduction section](documentation/readme-intro-section.png)

#### **The About us section**

The About us-section provides the user a little bit more detailed information about what Studio dancers offers that is useful for the to know what they can expect if they sign up for a class. Directly below the information a link is provided to the schedule for the dance classes, so that the user can reach it fast and easy without having to go to the navigation bar again. The link is highlighted in pink and changes to white when hovering over it. 

![About us section](documentation/readme-about-us.png)

#### **The Contact section**

The contact section lets the user know that questions can be asked if needed and provides the user with a phone number, email address and street address which the user is encuraged to use if there are any questions. To make it as useful as possible for the user, the contact details is provided on the home page so that the user early on in its journey at the site knows that questions can be asked if needed.   

![Contact section](documentation/readme-contact.png)

### **The Classes page**

The classes page is useful to the user as it provides important information about all the dance classes in order for the user to know what to sign up for. It contains information about where the classes are held; what dance styles Studio dancers offers classes in; when and how many weeks the classes are held; names of the instructors and prices for the classes. Above the text information about each dance style there is an image showing dancers dancing that specific style. Below the text information for each style there is a link to the sign up page. The link is placed there, and also highlighted in pink, to make it very easy for the user to find the form. The links turns white when hovering over them.  

![Classes page](documentation/readme-classes.png)

### **The Sign up page**

This page is useful to the user as it makes it possible to sign up for classes. The page provides a form with a submit button in the end, that collects the details needed to sign up; choice of class and contact details. The submit button is highlighted in pink to try to remind the user to not forget to send the form. The buttons becomes white when hovering over it.     

![Sign up page](documentation/readme-sign-up.png)

### **The Thank you page**

The purpose and value of the thank you-page is simply to ensure the user that the form has been sent and inform them that Studio dancers will contact them. It only contains a few short sentences, to not keep the user at this page longer than necessary. 

![Thank you page](documentation/readme-thank-you.png)

### **Future features**

- A news or calender section at the home page showing what events the dancers will attend soon. 
- Add a gallery to show how what a great dancer the user can be and how fun the user can have with Studio dancers. 

## **Testing**
---

The [WebAIM Contrast checker](https://webaim.org/resources/contrastchecker/) has been used to test that the contrast between the colors used is sufficient. At first, the pink color didn´t pass one of the tests for normal sized text. I changed the color to a slightly brighter one, then all colors passed all tests.   

The site has been tested so that it works on different browsers. It has been tested on Google Chrome, Microsoft Edge, Firefox and Samsung Internet. 

I have confirmed that the links on the site are not broken and works as intended and that all text is readable. 

I have also checked that the form on the sign up page is validated.

I have used [Responsinator](http://www.responsinator.com/) and the DevTools toolbar to test responsiveness and make the site look good on different screen sizes. 



### **Validator testing**

I have validated my code with the below websites. 
- HTML: [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) 
- CSS: [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)

!!!!!!!!!!!!!!!!!!!!!!!

The deployed site returns no errors. 

I also checked the accessibility of the site with Lighthouse in DevTools. The results for the final page is shown below. The first time I checked the accessibility, the score was lower than shown below. I increased the score by using compressed images that made the site load faster. I also added aria-labels to the images on the classes page. 

![Lighthouse testing score](INFOOOOOOGGGAA RÄTTTT LÄNK när du deployat)

### **Bugs**

#### **Resolved bugs**

When testing the site in different browsers I saw a dark thin line across the footer and a blue thin line right below the footer. I located the lines to be borders of elements within the footer and solved it be giving blue background color and increasing the line-height to divs in the footer. 

When testing responsiveness, large gaps appears for the smaller screen sizes between the information about the different classes. The problem was due to heights for the divs containing the information having vh-values. To solve it I gave only the biggest screen sizes a vh-value and the smaller once a px-value. 

After adding aria-labels to the images at the classes page, testing the website again showed me that the labels was incorrectly added. This was solved by adding a role-attribute to the divs where the aria-label was added. 




No bugs have been idenitified in the deployed version.

## **Deployment**
---
You can find the link to the live site [here.]( ADD LINK!!!!!!!!!!!!! )

The site was deployed to Github Pages with the following three steps:

1. Log on to GitHub
2. Find the correct repository 
3. Find the settings tab in the repository navigation bar
4. Find the pages option in the bar on the right hand side
5. In the source drop-down menu select the master branch ??????????????





6. Click the save button
7. The site is published and the URL for it is now provided in the bar directly under the GitHub Pages

## **Credits**
---
### **Content and design**

Code from [W3Schools website section about grid view](https://www.w3schools.com/css/css_rwd_grid.asp) has been used in the style.css file to create a grid and make the Studio dancers site responsive. Comments have been added in the code to show where the borrowed code is.

In order to increase the accessibility score for the page I had to add aria-labels to the images at the classes page. In order for the syntax to be correct (by adding a role-attribute) I used this [W3SC website](https://www.w3.org/TR/html-aria/#docconformance-naming) to guide me. 

Information on how to [build forms](https://www.w3schools.com/html/html_forms.asp) and what [different input types](https://www.w3schools.com/html/html_form_input_types.asp) that are available to create a valid sign up form was used from W3Schools website. 

[The css-ticks site](https://css-tricks.com/multiple-class-id-selectors/) was used to understand and create a selector that targets a class under another class.  

I have used this [dance studio web theme](https://themeforest.net/item/dance-studio-wordpress-theme/20555996) and this [Vibez web theme](https://themeforest.net/item/vibez-a-dynamic-multiconcept-theme-for-dance-studios-and-instructors/19654985) at [Themeforest](https://themeforest.net/), along with the website for [Rydbergs dance academy](https://rydbergsdance.com/) as inspiration for the design and layout of the page. 

https://www.w3schools.com/cssref/pr_background-image.php

LOVE RUNNING!

MMMMEEEERRR!!!!!!!!!!!!!!!!!!!! Inspiration till iconer i footer fick jag från Love Running project and 

[Google Fonts](https://fonts.google.com/) was used to import 'Montserrat subrayada' and 'Roboto condensed' fonts and [Font Awesome](https://fontawesome.com/) was used to import icons. 

[Fontpair](https://www.fontpair.co/all) was used to try to find fonts that look good together. 

[Adobe color](https://color.adobe.com/sv/create/color-wheel) was used to try to find colors that gives a good feeling to the site.  

The readme.md files for the [Love running project](https://github.com/Code-Institute-Solutions/readme-template), [the Coding club project](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+CSSE_PAGPPF+2021_Q2/courseware/66cf361c769a41d496f5001fae6f9be7/3b5cd5dc8313462aa5975a3c9b9a1a3c/) and [Angie´s Beauty website](https://github.com/AmyOShea/Angies-Beauty-MS1) has been used for inspiration for the content of the readme.md file for this site.

### **Images**

The images used on the site have been taken from [Unsplash](https://unsplash.com/) and [Pexels](https://www.pexels.com/sv-se/). The specific links to each image are listed below.

Unsplash:
- [happy-group-medium.jpg](https://unsplash.com/photos/GRDpPpKczdY)
- [stage-group-medium.jpg](https://unsplash.com/photos/_v8C6BlpBzY)
- [ballet-medium.jpg](https://unsplash.com/photos/nZU76qWy-T8)
- [contemporary-medium.jpg](https://unsplash.com/photos/n-g7dgwNZg4)

Pexels:
- [five-girls-medium.jpg](https://www.pexels.com/sv-se/foto/vanner-kvinnor-kondition-traning-8957649/)
- [jazz-medium.jpg](https://www.pexels.com/sv-se/foto/manniskor-dans-sport-rorlig-12312/)
- [hiphop-medium.jpg](https://www.pexels.com/sv-se/foto/gata-man-rorelse-ung-5368956/)

[Tinypng](https://tinypng.com/) was used to compress the images.

## **Acknowledgments**
---

I want to thank my mentor Antonio Rodriguez for guiding me when building this site to make it responsive with grid view.








