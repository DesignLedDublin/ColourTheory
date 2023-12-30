# Colour Theory

Colour Theory is a site created by interior design studio, DesignLed, which helps users find the colours to use to make them love their home. The website gives users general knowledge about colour theory and how different colours affect mood. In addition, it provides some colours palettes visitors can use as a base to start decorating their home as well as instructions on how to implement them. View the live site [here](https://designleddublin.github.io/ColourTheory/index.html)

![Mockup](/assets/Readme%20Images/All-devices.webp)

# Design

### Colours

* The feature colour of #580b20 is used throughout the site to highlight key elements on a page and for icons. 
* The feature colour of #dc9806 is used when items in the menu bar or social icons are hovered over.
   ![HoverColour](/assets/Readme%20Images/Header-palettes-clicked.webp)

### Fonts 
* Fonts used are Arial Narrow Bold and Grandiflora One

### Images 
* All images are from my design studio work, DesignLed. 
* The logo was created by me for this project. 

### General design points
  * The footer border is replaced with a custom-designed rainbow line to link in with the colour theme of the website.
  ![Footer](/assets/Readme%20Images/Footer.webp)



# Features 

This website consists of 8 pages.  Six are accessible from the navigation menu.  One is a 404 error page and one is a submission confirmation page for the contact form. 

### Navigation Menu
  * On the left hand side is the site logo, this moves to the center on mobile devices.  
  * On the right hand side there are four links or burger menu on smaller screens:
    * Home
    * What is Colour Theory
    * Palettes dropdown menu pages
    * Contact page 
  * The user can decide to have the Palettes dropdown menu open or closed by clicking the Palettes menu item to both open and close it. 
   ![Dropdown](/assets/Readme%20Images/Header-dropdown-menu.webp)
___

### Footer
  * To the right are social media icons.  The social links go to DesignLed's social media pages.  Icons are accessible to the visually impaired who may be using a screen reader with the use of aria labels.  
  * To the left is the copyright to DesignLed for the website, this also links to the DesignLed website in case users would like to see the studio's website.
  * This will allow the user to follow DesignLed if they would like to after visiting the Colour Theory page. 
___
### Favicon
  * A site wide favicon has been implemented with the Colour Theory logo.
  * This will provide an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open.
___
### 404 Page
  * A 404 page has been implemented and will display if a user navigates to a broken link.
  * The 404 page will allow the user to easily navigate back to the home page of the website with a button to take them directly to it. 
  ![404](/assets/Readme%20Images/404.webp)
___
### Form Submission Page
  * This shows once the submit button has been pressed on the contact page.  After ten seconds, it automatically redirects to the home page.    
   &nbsp;
# Project Screenshots

### Home Page:

![HomePage](/assets/Readme%20Images/Home.webp)
* Landing page header
  * The landing page header - How to use Colour in Your Home - will immediately explain what the website is for.

* Landing page carousel
  * This will be a collection of DesignLed's projects that show a strong use of colour.
  * It will help to animate the page and inspire the user.

* Sub heading
  * This will serve to reiterate to the user what the website is for and how it will help them learn how to use colour in their home.

* Coming Soon Section
  * This section is to get the user excited about the colour personality quiz which we will soon be releasing.
___

### What is Colour Theory Page:

![ColourTheory](/assets/Readme%20Images/Colour-Theory.webp)
* This page is designed to give users background information about colour theory and what different colours mean.
* The images and corresponding text are responsive and will allow the user to view content from any device.

___

### Palettes drop down menu:

![ColourTheory](/assets/Readme%20Images/Palettes.webp)
- The format of these three pages is the same. It gives visitors some general information about this type of colour palette. Shows a room decorated with this colour palette with a sample palette pulled from this room and then gives a 'How To' section that gives visitors pointers on how to implement a palette like this in their own home. The three palettes explored are:
  - Neutral
  - Monochromatic
  - Maximalist
___

### Contact Page:
![Contact](/assets/Readme%20Images/Contact-page.webp)
* This page gives a contact form that enables people to contact DesignLed directly.
* The contact detail sections are required so that a user cannot submit the form with no information. 
* It also gives contact details for DesignLed if people would prefer to use these.
&nbsp;  
&nbsp;

# Existing Features

* Responsive design
* Drop down menu for palettes section
* Bootstrap footer border changed to rainbow line designed inhouse
* Contact form and success page
* Link hover colour change
&nbsp;  
&nbsp;


# Features Left to Implement

* A quiz page will be added to enable people to find their colour style for their home.
* As a future enhancement, the contact form will be updated with javascript to send an email to DesignLed when submit is clicked. 
&nbsp;  
&nbsp;

# Technologies

* HTML
  - The structure of the Website was developed using HTML as the main language.
* CSS
  - The Website was styled using custom CSS in an external file.
* Visual Studio Code
  - The website was developed using Visual Studio Code IDE
* GitHub
  - Source code is hosted on GitHub and delpoyed using Git Pages. Github was also used to commit and push code during the development opf the Website
* Font Awesome
  - Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section.
* www.birme.net
  - This was used on all images to both compress and convert them to .webp format./
* Favicon.io
  - favicon files were created at https://favicon.io/favicon-converter/
* Sketch
  - wireframes were created using sketch.com
&nbsp;  
&nbsp;

# Testing

## Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Safari browsers.

Steps to test:

1. Open browser and navigate to [Colour Theory](https://designleddublin.github.io/ColourTheory/)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

Actual:

Website behaved as expected with the exception of ipad screen when one of the social icons in the footer went below the line of the others.  I was not able to fix this, please see unfixed bugs. 

Website was also opened on the following devices and no responsive issues were seen:

* Ipad 5th Generation
* Acer Travelmate Laptop
* Iphone - put in model
* Samsung S21 FE 

## Validator Testing 

### HTML
 [W3C validator](https://validator.w3.org)
 Initially the following issues were found:
 * There were multiple trailing slash on void elements found.
 * For all the img elements, I had to take out the px as this wasn't allowed in the width and height elements. 
 * The automatic redirect for the contact-form-submit.html was not in the head section of the website so this had to be moved. 

 Once I had corrected these issues, there were no further errors found when passing it through the W3C validator.
![HTML](/assets/Readme%20Images/HTML-checker.webp)

 ### CSS
 [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
Initially, there the issues below with my CSS code:
![CSSErrors](/assets/Readme%20Images/CSS-validator-issues.webp)

Once I removed these CSS elements, no errors were found:
![CSSClear](/assets/Readme%20Images/CSS-validator-clear.webp)
&nbsp;  

# Issues found during site development 

### Creating the dropdown menu in navbar menu 
  * When I used code from Boostrap, it gave me a button instead of a dropdown menu item that looked the same as the rest of the menu.  [This article](https://www.w3schools.com/bootstrap4/bootstrap_dropdowns.asp#:~:text=Basic%20Dropdown&text=To%20open%20the%20dropdown%20menu,actually%20build%20the%20dropdown%20menu.) enabled me to get this element to look right, but the menu wouldn't drop down.
  * I tried changing to v5 of Bootstrap as I read that you need this to make the dropdown toggle but this made everything go out of aligment.  I eventually found [this article](https://stackoverflow.com/questions/22955916/bootstrap-collapse-not-collapsin) which made me realise that if I took the -bs- out of the data-bs-toggle and went back to v4 of Bootstrap the drop down menu works and the alignment works. 

### Adding required action to the form inputs on the Contact page
  * The form template I was using did not have this function.  When I added the required instruction, it did not work.  
  * [This page](https://stackoverflow.com/questions/60058280/required-attribute-not-working-with-form-tag) made me realise the form was missing the submit specification.
  * This still didn't work and I realise looking at the code that the <form></form> section was closed before the submit section.  I moved this underneath the submit section and added 'formaction' instead of 'href' after reading [this article](https://www.w3schools.com/tags/att_button_formaction.asp) and it worked. 

### Endless horizontal scroll in How To section on Palettes page
  * [This article](https://medium.com/afosto/bootstrap-v4-explained-the-grid-and-how-to-use-it-82a4de58604e) told me the container fluid class doesn’t have a max width.
  * So I used advice from [this article](https://mdbootstrap.com/docs/standard/extended/max-width/#:~:text=In%20order%20to%20make%20an,w%2D100%20class%20to%20it.&text=You%20can%20also%20use%20max,100%25%3B%20utilities%20as%20needed) to set a max width and the problem was solved. 
&nbsp;  
&nbsp;

# Unfixed Bugs 
* I could not get the social icons to sit all in one line on ipad size.  I will fix this in a future release. 
&nbsp;  
&nbsp;
  
# Credits 

To complete this project, I used Code Institute student template [gitpod full template](https://github.com/Code-Institute-Org/gitpod-full-template)

I used Boostrap code for some parts of my website, this is noted in the code. 
&nbsp;  

## Code 

* [Dropdown menu in navbar](https://www.w3schools.com/bootstrap4/bootstrap_dropdowns.asp#:~:text=Basic%20Dropdown&text=To%20open%20the%20dropdown%20menu,actually%20build%20the%20dropdown%20menu.)
    * I used code from this page to help me create the dropdown menu without a button where the dropdown is, which is what I was getting from the Navbar Bootstrap code. 
* [Contact Form base code](https://mdbootstrap.com/docs/b4/jquery/forms/contact/#html)
    * This is where I got the base code for my contact form.  I then adapted it to my needs. 
* The base code for the 404 page came from this site:
https://frontendshape.com/post/bootstrap-5-404-page-examples
&nbsp;  

## Images
* All images belong to me, any additional design elements were created by me for this project. 
&nbsp; 

## Content
* All content is original and generated by me.

