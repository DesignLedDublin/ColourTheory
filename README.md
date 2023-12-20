# Colour Theory

Colour Theory is a site created by interior design studio, DesignLed, which helps users find the colours to use to make them love their home. The website gives users general knowledge about colour theory and how different colours affect mood. In addition, it provides some colours palettes visitors can use as a base to start decorating their home as well as instructions on how to implement them. View the live site [here](https://designleddublin.github.io/ColourTheory/index.html)

![Mockup](/assets/Readme%20Images/All-devices.webp)

## Features

### Site wide

* General design points

  * The feature colour of #580b20 is used throughout the site to highlight key elements on a page.
  * The feature colour of #dc9806 is used when items in the menu bar or social icons are hovered over.
   ![HoverColour](/assets/Readme%20Images/Header-palettes-clicked.webp)
  * The footer border is replaced with a custom-designed rainbow line to link in with the colour theme of the website.
  ![Footer](/assets/Readme%20Images/Footer.webp)

* Navigation Menu
  * Contains links to the Home, What is Colour Theory pages, Palettes dropdown menu pages and Contact page and will be responsive on all devices.
  * This will allow users to easily navigate between the pages within the site on any size device.
  * The user can decide to have the Palettes dropdown menu open or closed by clicking the Palettes menu item to both open and close it. 
   ![Dropdown](/assets/Readme%20Images/Header-dropdown-menu.webp)

* Footer
  * This contains icons as links to social media websites that open in new tabs.  The links will link to DesignLed's social media pages.  Icons will be accessible to the visually impaired who may be using a screen reader with the use of aria labels. It will also contain a copyright to DesignLed for the website, this line will also link to the DesignLed website in case users would like to see the studio's website.
  * This will allow the user to follow DesignLed if they would like to after visiting the Colour Theory page. 

* Favicon
  * A site wide favicon has been implemented with the Colour Theory logo.
  * This will provide an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open.

* 404 Page
  * A 404 page has been implemented and will display if a user navigates to a broken link.
  * The 404 page will allow the user to easily navigate back to the home page of the website with a button to take them directly to it. 
  ![404](/assets/Readme%20Images/404.webp)

### Home Page

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

### What is Colour Theory Page

![ColourTheory](/assets/Readme%20Images/Colour-Theory.webp)
* This page is designed to give users background information about colour theory and what different colours mean.
* The images and corresponding text are responsive and will allow the user to view content from any device.

### Palettes drop down menu

![ColourTheory](/assets/Readme%20Images/Palettes.webp)
- The format of these three pages is the same. It gives visitors some general information about this type of colour palette. Shows a room decorated with this colour palette with a sample palette pulled from this room and then gives a 'How To' section that gives visitors pointers on how to implement a palette like this in their own home. The three palettes explored are:
  - Neutral
  - Monochromatic
  - Maximalist

### Contact Page
![Contact](/assets/Readme%20Images/Contact-page.webp)
* This page gives a contact form that enables people to contact DesignLed directly.
* It also gives contact details for DesignLed if people would prefer to use these.

### Existing Features

* Responsive design
* Drop down menu for palettes section
* Bootstrap footer border changed to rainbow line designed inhouse
* Contact form and success page
* Link hover colour change

### Features Left to Implement

* A quiz page will be added to enable people to find their colour style for their home.
* As a future enhancement, the contact form will be updated with javascript to send an email to DesignLed with the contact information.

## Technologies

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

## Testing

### Responsiveness

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

* Ipad- put in model
* Iphone - put in model
* Samsung S21 FE 

### Validator Testing 

- HTML
 [W3C validator](https://validator.w3.org)
 Initially the following issues were found:
 * There were multiple trailing slash on void elements found.
 * For all the img elements, I had to take out the px as this wasn't allowed in the width and height elements. 
 * The automatic redirect for the contact-form-submit.html was not in the head section of the website so this had to be moved. 

 Once I had corrected these issues, there were no further errors found when passing it through the W3C validator.
![HTML](/assets/Readme%20Images/HTML-checker.webp)

 - CSS
 [W3C CSS validator](https://jigsaw.w3.org/css-validator/)
Initially, there the issues below with my CSS code:
![CSSErrors](/assets/Readme%20Images/CSS-validator-issues.webp)

Once I removed these CSS elements, no errors were found:
![CSSClear](/assets/Readme%20Images/CSS-validator-clear.webp)


 ### Lighthouse Testing
Initially I had issues with the performance element of this result on the home page only, it was at 86.  
To bring this score up, I made a few changes:
* I made the size of the logo in the navbar smaller. 
* I made the size of the carousel images on the home page smaller. 
* All other pages had scores above 90 straight away. 
![LightHouse2](/assets/Readme%20Images/Lighthouse-ColourTheory.webp)
![LightHouse3](/assets/Readme%20Images/Lighthouse-Palettes.webp)
![LightHouse4](/assets/Readme%20Images/Lighthouse-Contact.webp)

## Bugs 
* Creating the dropdown menu in navbar menu 
  * When I used code from Boostrap, it gave me a button instead of a dropdown menu item that looked the same as the rest of the menu.  [This article](https://www.w3schools.com/bootstrap4/bootstrap_dropdowns.asp#:~:text=Basic%20Dropdown&text=To%20open%20the%20dropdown%20menu,actually%20build%20the%20dropdown%20menu.) enabled me to get this element to look right, but the menu wouldn't drop down.
  * I tried changing to v5 of Bootstrap as I read that you need this to make the dropdown toggle but this made everything go out of aligment.  I eventually found [this article](https://stackoverflow.com/questions/22955916/bootstrap-collapse-not-collapsin) which made me realise that if I took the -bs- out of the data-bs-toggle and went back to v4 of Bootstrap the drop down menu works and the alignment works. 

## Unfixed Bugs 
* I could not get the social icons to sit all in one line on ipad size.  I will fix this in a future release. 
  
## Credits 

* [Dropdown menu in navbar](https://www.w3schools.com/bootstrap4/bootstrap_dropdowns.asp#:~:text=Basic%20Dropdown&text=To%20open%20the%20dropdown%20menu,actually%20build%20the%20dropdown%20menu.)
    * I used code from this page to help me create the dropdown menu without a button where the dropdown is, which is what I was getting from the Navbar Bootstrap code. 
* [Contact Form base code](https://mdbootstrap.com/docs/b4/jquery/forms/contact/#html)
    * This is where I got the base code for my contact form.  I then adapted it to my needs. 

### Content and Media

All content and media are owned by Lisa Marconi through her company Design Led Ltd.  The logo was created by Lisa Marconi for this project. 
