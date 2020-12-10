# Love Food Stop Waste

---

![live demo](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/images/responsive-design.jpg "live demo") 



## Demo
---
[Live demo :point_left:](https://nazulka.github.io/Love-food-stop-waste/index.html)
[GitHub repository :point_left:]()


---
## About 
---
This website aims to raise awareness of the food waste problem and offers some easy steps we can all take at home to save money and 
keep the valuable resources used in food production and distribution from going to waste.


## UX
---
### This website will appeal to:

* **Environmentally conscious citizens**
    * I want to be able to better understand the way the Earth's resources are currently being used for production and distribution of food.
    * I want to get a better understanding of the food waste problem in order to take action to fight it.
    * I want to know easy tips on ways of being kinder to the environment, help conserve energy and resources.

* **Concerned consumers**
    * I want to educate myself / my family about climate change, greenhouse gases and food waste.
    * I want to reduce food waste in my household and save money from buying less food.
    * I want some creative meal or snack recipe ideas using simple ingredients and leftovers.
    * I want to receive a newsletter with ideas on how to stop food waste and new recipes that use common leftover foods.


### Wireframes 
* [Home Page](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/wireframes/home.png)
* [Plan Page](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/wireframes/plan.png)
* [Leftovers Page](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/wireframes/leftovers.png)
* [Contact Us Page](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/wireframes/contact.png)
* [Tablet View All Pages](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/wireframes/tablet-view.png)
* [Mobile View All Pages](https://github.com/Nazulka/Love-food-stop-waste/blob/main/assets/wireframes/mobile-view.png)

## Features
----
### Existing Features

#### Features used across all pages
* **Header**
    * Header - navigation bar has been built using Bootstrap "fixed-top" class to allow easy navigation for users throughout the website. 
    It is positioned on top of the page and remains visible on all screen size devices.
    * Navigation bar includes a brand logo and links to the four pages of the website: Home, Plan and Store, Love your Leftovers and Contact Us.
    * Navigation links are collapsed in small screen sizes into a hamburger menu. 
    * Brand logo serves as a Home page link, in addition to the Home link in the navbar. It is particularly convinient for users accessing the website on 
    smaller screen devices to get back to the Home page without having to use the hamburger menu.
    * All navigation links change color to green on hover and the current page's link stays "active", so the users can easily identify the page they are on.

* **Footer**
    * Footer has been designed using Bootstrap, it is fixed to the bottom of the page and takes up the whole width of the screen on all devices.
    * It contains four social media icons in the center of the footer bar.
    * These icons change color on hover to green to let the users know they are clickable (similar to the links in the navigation bar) and are 
    lnked to the external social media websites, which open in a new tab.

* **Socket**
    * Socket section is located below the footer and contains copyright symbol and the website address, which changes color to green on hover and is linked to 
    the Home page of the website.

    
#### Features specific for the pages
* **Home** 
    * Main banner image is intended to be colorful and bright to draw attention.
    * Bootstrap jumbotron with a heading: Love Food Stop Waste, contains main message and call to action "Find Out More" button, if users wish to explore further, 
    which opens a page for [The Waste and Resources Action Programme (WRAP)](www.wrap.org.uk) in a new tab.
    * Food Facts - Bootstrap jumbotron with a custom colored background and Font Awesome icons to provide visual image and draw users' attention to the 
    information in the section. 
    * Info section followed by three column section, with images to support the text accordingly.

* **Plan** 
    * This page contains an image that represents it's content followed by a jumbotron with a custom background.
    * The Reduce Food Waste section describes the two main ways to achieve that and followed by two column Bootstrap card section. 
    Each card consists of an image to visually support the content of the section and two paragraphs of text.
   
* **Leftovers**
    * The heading of the page is placed on an image and located on top of the page.
    * It is followed by a text section and three column card section. The card with a new recipe contains Bootstrap Badge "New" so users can identify new content. 
   
* **Contact**  
    * This page contains a "Subscribe for a newsletter" form designed using Bootstrap's JS Modal plug-in. 
    There are four fields on the form: First Name, Last Name, Email (required fields) and Your Message (optional text field).
    * The modal has a custom background to make the page more inviting to the users.


### Features Left to Implement

* To make the website more child-friendly through adding colourful images, fun activities that help children to understand food waste problem and lots of creative easy leftover recipe ideas for children. 
* To add a new page "Food Share" with a map and addresses to show the local community food bank locations if users wish to donate food items, 
as well as using the food bank's services. This will broaden the user pool and strenthen the website's role in the community.


## Technologies Used
___
* Languages Used
    * **HTML5**
    * **CSS3**

* Frameworks, Libraries and Programs Used
    * *Bootstrap v4.2.1* - used for faster and easier web development. Bootstrap's components, such as, navbar, jumbotron, buttons, modal, cards have been 
    used to create a responsive website.
    * *Font Awesome* - Font Awesome icons have been added to "Food Facts" and Footer sections
    * *Google Fonts* - "Monserrat" font has been imported to style the whole website.
    * *jQuery* and *Popper.js* plugins - included to be able to use some of the Bootstrap components, such as, navbars, buttons, modals and other clickable components.
    * *Git* - used for version control and tracking changes.
    * *Gitpod* - used as a development environment and allowed me to add, commit and push files to GitHub.
    * *GitHub* - used as a hosting platform for version control and future collaborations.


## Testing
___
This website has been tested using:
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
* [W3C HTML Validator](https://validator.w3.org/)
No errors were found. 


### Testing User Stories from UX section of this file

* **Environmentally conscious citizens' goals** 
    * I want to be able to better understand the way the Earth's resources are currently being used for production and distribution of food.
        * The information to satisfy the above users' goals is placed in the "Love Food Stop Waste" section of the Home page. 
        * The Home page is easy to access either by clicking on Home link on the fixed navbar or clicking on the brand logo. 
        * The clearly labelled call to action button invites users to find out more about this topic from Waste Resouses and Action Programme (WRAP) and opens in a new tab.
    * I want to get a better understanding of the food waste problem in order to take action to fight it.
        * "Food Facts" section is on the Home page and is easy to navigate to as descrided above.
        * More information can be found by clicking our Social links which are placed in the footer on every page of the website and open in new tabs.
    * I want to know easy tips on ways of being kinder to the environment, help conserve energy and resources.
        * A clearly labelled "You Can Make a Difference" section is easy to find by scrolling down to the bottom of the Home page
    and it is continued in the Plan and Leftovers Pages. Users intuitively move through these pages by using the navigation links.

         
* **Concerned consumers' goals**
    * I want to educate myself / my family about climate change, greenhouse gases and food waste.
        * The Home page has an engaging layout and can be found easily by clicking on the Home link in the navbar or brand logo from anywhere on the website.
        * The sections on the Home page are clearly labelled. Food Facts section's visually presented information satisfies above goals. 
        * The call to action button invites users to find out more in an external source that opens up in a new tab.
    * I want to reduce food waste in my household and save money from buying less food.
        * The Plan page is easy to find through navbar link and has clearly labelled sections that can be easily scrolled down to in order to achieve this goal. 
    * I want some creative meal or snack recipe ideas using simple ingredients and leftovers.
        * The Leftovers page is easy to navigate to and has clearly labelled information section as well as recipes section.
    * I want to receive a newsletter with ideas on how to stop food waste and new recipes that use common leftover foods.
        * A clearly labelled Contact Us page can be easily accessed via navbar link from anywhere on the website.
        * An easy to fill "Subscribe to a newsletter" form allows users to register their interest and receive a newsletter to their inbox.



### Further Testing

* **Functionality Testing**
    * Navigation Bar
        * The navbar is fixed and stays visible on top of all pages on the website on all screen sizes.
        * The navbar is responsive, this have been tested by reducing / increasing the screen width and is working as expected.
        * When the brand logo is clicked, it takes the users to the Home page from anywhere on the website.
        * All links on the navbar have been tested by clicking on the links and are working as intended.
        * The navbar collapses into a hamburger menu on screen sizes smaller than 768px. A navigation menu appears when you click on the hamburger icon. 
        Tests revealed that feature is working as intended, as well as all the navigation links. 

    * Footer
        * Footer always stays on the bottom of the page and is responsive. This have been tested by reducing / increasing the screen width and is working as intended.
        * Change of colour and transition effects on hovering over Social icons have been tested and working as intended. 
        * Click on each Social icon revealed they are working as intended and open up in a new tab.

    * Socket
        * Socket always stays on the bottom of the page below the footer and is responsive. This have been tested by reducing / increasing the screen width and is working as intended.
        * Change of colour and transition effects on hovering over the website address have been tested and working as expected. 

    * Call to action button on Home page
        * Hover over call to action button has been tested and confirmed color change.
        * Click on call to action button has been tested and it works as intended. A webpage link opens up in a new tab.
    
    * Contact form on Contact Us page
        * The Contact form has been tested by:
            * Submitting the form with one or more empty required fields. This returns an error message requesting to fill in all the requested fields.
            * Filling in text input into email field. This returns an error "@ sign should be included in the email address". This however doesn't stop users from entering incorrect email address.
            * Filling in all input fields with valid data and clicking "Subscribe" button returns the form to it's initial state. 


* **Usability Testing** 
    * This website was shared with friends and family to test it's usability and identify any issues. 
    They found the website easy to use, were able to intuitively navigate through the pages and didn't experience any other issues. 

    
* **Compatibility Testing**
    * Compatibility and responsivness of the website was extensively tested across multiple browsers (Chrome, Safari, Microsoft Edge, Fire Fox) and on muliple screen size devices 
    (iPhone 5, 6, 7, PLus, X, Microsoft Lumia 950; Kindle Fire HDH, iPad, iPad Pro, Samsung Galaxy S5) using Chrome Devtools.
    Initial tests revealed that on all browsers on the first two pages the fixed navbar was scrolling up halfway. It was identified that the overflow of the images below caused this bug. 
    This bug was fixed by adding `col-12` and `px-0` Bootstrap classes to the divs. 


### Known Bugs
* There are no other known bugs at the time of submitting this project.


## Deployment
___
All code for this website was written in Gitpod and then pushed to GitHub to store in the local repository. 
It was then published using GitHub Pages directly from the *main branch* by following steps below:
* Select **Love Food Stop Waste** in *your repositories*
* Click on **Settings** in the menu bar
* Scroll down to **GitHub Pages** and select *main branch* in drop-down menu in the **Source** section
* The page will reload and you'll be provided with a link to your published website.

You can 
There is no difference between the deployed version and the development version.


## Credits
___
### Content
* **Home**
    * Home page Love Food Stop Waste section content has been taken from [Love Food Hate Waste](https://lovefoodhatewaste.com/) and
     [The Waste and Resources Action Programme](https://www.wrap.org.uk/content/we-wont-fix-climate-change-if-we-dont-stop-wasting-food).
    * Food Facts section content has been partially taken from [Friends of the Earth](https://friendsoftheearth.uk/food-waste) and also been supplemented by additional information to suit the needs of the website.
    * Get composting section content has been taken from [The RHS](https://www.rhs.org.uk/advice/profile?PID=444).

* **Plan and Store**
    * Content for this page has been taken from [Food Standard Agency](https://www.food.gov.uk/food-safety) and [Love Food Hate Waste](https://www.lovefoodhatewaste.com/why-save-food).

* **Love Your Leftovers**
    * Content for this page has been taken from [Stop Food Waste](https://stopfoodwaste.ie/resource/leftovers) website and also inspired by [Friends of the Earth](https://friendsoftheearth.uk/food-waste).
    * Recipes:
        * 5-a-day tagine - [BBC Good Food](https://www.bbcgoodfood.com/recipes/5-day-tagine)
        * 5 ways to use leftover bread - [Love Food Hate Waste](https://www.lovefoodhatewaste.com/article/5-ways-use-leftover-bread)
        * Leftover chicken enchiladas also from the website above and can be found [here](https://www.lovefoodhatewaste.com/recipe/leftover-chicken-enchiladas)

### Media
The images used in this website were obtained from free stock images websites [Unsplash](www.unsplash) and [Pexels](www.pexels.com) and compressed using [TinyPNG](https://tinypng.com).

* Home 
    * Main banner image [Photo by Trang Doan from Pexels](https://www.pexels.com/photo/sliced-fruits-on-tray-1132047/)
    * Three column section images are by [Priscilla Du Preez](https://unsplash.com/photos/urcDzLL0HnI), [Photo by Vladislav Vasnetsov from Pexels](https://www.pexels.com/photo/assorted-color-plastic-trash-bins-2682683/) and [Markus Spiske](https://unsplash.com/photos/2XZ-tIRRt04). 

* Plan 
    * Main banner image [Photo by Vegan Liftz from Pexels](https://www.pexels.com/photo/blue-ceramic-plate-with-meal-plan-blocks-2377165/)
    * Plan and Store section background image [Photo by Lauren Mancke from Unsplash](https://unsplash.com/photos/sil2Hx4iupI). A filter has been applied to this image to balance the contrast between the image and the text over it. 
    * Two column Bootstrap cards section images are by [Micheile Henderson](https://unsplash.com/photos/iVC56eIVq-c) and [Cathryn Lavery](https://unsplash.com/photos/fMD_Cru6OTk) from Unsplash.

* Love Your Leftovers   
    * Main banner image is by [Spencer Davies](https://unsplash.com/photos/vJsj-hgOEG0). A filter has been applied to this image to increase the contrast between the image and the text over it.
    * Images used in the cards section are by [Vicky Ng](https://unsplash.com/photos/yL9qjDDmmMU) and [Kevin McCutcheon](https://unsplash.com/photos/APDMfLHZiRA).

* Contact page background image [Photo by Ella Olsson from Pexels](https://www.pexels.com/photo/photo-of-vegetable-salad-in-bowls-1640770/)

### Acknowledgements
* Navigation Bar, Footer and Socket for this website were designed through following these video tutorial [by Drew Ryan](https://www.youtube.com/watch?v=9cKsq14Kfsw&t=773s) 
and also using tips from [MDBootstrap](https://mdbootstrap.com/docs/jquery/navigation/footer/) website. Considerable modifications were made to fit the purpose of the website.
* This tutorial by the same author has inspired sections with cards and horizontal rule and media queries [here](https://www.youtube.com/watch?v=TJF4ldO91n4&t=137s).  
* The CSS code line `object-fit: cover;` for Home page banner image was kindly provided by my mentor Excellence Ilesanmi.
* Tutor Support have been very helpful in pointing me to the right direction when I encountered the bug with the jumping navbar (as described in Testing section). 
* I have also referred to CI Video Tutorials on HTML, CSS and Bootstrap. 
* README samples have been helpful in writing the README.md file. 