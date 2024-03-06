
# The Plant Collection

The Plant Collection is a charming local destination nestled in Leeds, blending the pleasures of a cosy coffee shop with the vibrant allure of a plant haven. Our website is thoughtfully crafted to offer visitors an immersive glimpse into the essence of our business, inviting them to discover the unique fusion of coffee culture and botanical delights that sets us apart.

![](/assets/readme-images/responsiveUI.png)

## intro

The Plant Collection already has a good presence on social media, but they want a central hub for customers to understand why their coffee shop is different from others.

#### The main goals of this website for the site owner are:

  - Attract customers to the shop.
  - Give an overview of the business.
  - Show customers where it is and when it is open.
  - Allow repeat customers to see new menu items.
  - allow repeat customers to see what events are on.
  - create a website that is easily edited by a future developer.

## User Experience (UX)

- ### User stories

    - #### First Time Visitor Goals

      1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the         organisation.
      2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
      3. As a First Time Visitor, I want to find out where the shop is located and the opening times.

    - #### Returning Visitor Goals

      1. As a Returning Visitor, I want to find information about the new food a coffee available.
      2. As a Returning Visitor, I want to be added to a mailing list to receive updates on the shop.
      3. As a Returning Visitor, I want to find out what events are happening.

    - #### Frequent User Goals

      1. As a Frequent User, I want to check to see if there are any newly added menu items.
      2. As a Frequent User, I want to sign up for the newsletter so that I am emailed any major updates and/or changes to the website or organisation.

- ### Design

    - #### Colour Scheme

      - The page will use a dark green and lighter version mainly throughout the page. A secondary cream colour will be used as a highlight. These are the Plant collections colour schemes they use with the business.

    - #### imagery
      - imagery is very important for this business, as one of the main drivers of what makes this coffee shop different is the look and style of the business.
      - all images will be taken from the business as they properly portray the aesthetic of the shop.

- #### font
- the font HeroinePro should be used for all titles and Aliana for all other text. This has been expressed by the owners as it fits their online presence and imagery.

![Fonts](/assets/readme-images/screenshot-fonts.png)

I have had issues getting these fonts to work on the website. This could be a future feature to add.

- ### Wireframes
<details>

 <summary>Desktop Wireframe</summary>

![Desktop Wireframe](/assets/readme-images/desktop-writeframe.png)

 </details>

 <details>
    <summary>Mobile Wireframe</summary>

![Mobile Wireframe](/assets/readme-images/mobile-wireframe.png)

 </details>

Originally, the hero was going to be one image, but the two image hero fits better with the two column layout of the desktop site,one image is used when on mobile.

The reviews section was removed as per discussion with the site owner, as they wish to later have the reviews be the most recent reviews using the Google Reviews API; this could be a feature later added.

## Features

### scale and Editing for Future Developers

To improve load times as the website is it is only small, I didn't use bootstrap, I created my own CSS utilities library and CSS variables for developers to quickly change the style or add new content.

#### CSS variables

There are variables for the main Color theme of the page, which can be quickly changed from the variables.

- primary-clr
- primary-clr-light
- primary-clr-dark
- secondary-clr
- accent-clr

- ff
  The family font of all text can be changed using this.

There are also variables for font weight and size, these have been used with various heading and body text utilities similarly named.

- fw-normal
- fw-medium
- fw-bold

- fs-heading
- fs-subheading
- fs-emphisised-body
- fs-body
- size-(200-900)

  These can be changed with a media query if different font sizes need to be used on a smaller screen.

#### Css utilities

These follow the same naming convention, but I will explain any differences here.

- color-(primary,secondary,accent)
  This changes the text color

- bg-color-()
  This changes the background color
- padding-block-(400-900)
  This will apply all around padding to elements.

- container
  This is a general container for content on the page and gives an automatic margin to anything within it.

  This has two local variables that can be changed to quickly change the amount of margin on all content using .container

  - LV max-with
  - LV vertical-padding

- button
  general styling for any button or link with hover effects

- even-columns
  This is used to set an even grid of elements. The site generally uses a two column layout, but three is also used on some sections.

  This will break into one column layout on mobile.

## Home Page Features

### Navigation

- The navigation is at the top of the page and allows a user to quickly access links to the Home, About Us, Events, and Contact Us pages.
- The navigation highlights what page the user is on.
- When on small mobile devices, the large title will not be displayed to make the UI less cluttered.

![Nav Bar](/assets/readme-images/screenshot-navbar.png)

### The landing page

- the landing page includes the business logo and location, as well as a hand drawn image of the shop to draw the user in while keeping with the minimalist style of the business and the page.
- The drawn picture will not be displayed on very small screens, as this allows mobile users to quickly get to the information they are looking for.

![Hero](/assets/readme-images/screenshot-hero.png)

### The About section

- the about me includes a large title, "Who are we" and a picture of the owner inside the shop in a two page column on desktop. highlighting the main draw of the shop is that it is a local business with someone who really cares about it in charge.
- it also includes a quote taken from the owner about the conception of the business and what the shop aims to be.

![About us](/assets/readme-images/screenshot-whoarewe.png)

### featured section

The Plant Collection does not sell the same products all year round and has specials on certain products that will only be in for a limited time.

- this section features a one column layout on desktop, highlighting the product.

- the image draws a customer to see a highlighted product that the business is selling that week, with a description of the product underneath.

![Featured](/assets/readme-images/screenshot-featured.png)

### Coffee, Plants and Local

- these sections all display the three different aspects of the business and go into more detail about each one.
- a image is included to highlight the differences between each one.
- a link is included at the bottom that will send them to the larger section on each aspect of the about me page.

![Sections](/assets/readme-images/screenshot-coffee.png)
![Sections](/assets/readme-images/screenshot-plants.png)
![Sections](/assets/readme-images/screenshot-local.png)

### location and opening times section

- this section includes key information on where the shop is located, when it is open, and what the business sells.

![Location](/assets/readme-images/screenshot-footer-location.png)

### footer

- the footer displays links to the social media accounts of the plant collection.
- it also displays a sign up for an email list.

![footer](/assets/readme-images/screenshot-footer.png)

## About page features

### Hero Section

-this section gives an overview of the business's aims and culture.
-it contains an image of the home made food served at the plant collection to show its authenticity.

![About us hero](/assets/readme-images/screenshot-aboutus.png)

### additional information
- when recieving feedback from the owners, they sent over more content and a description to add to the about me to let customers know more about the business and its aims.

![About us Additional](/assets/readme-images/screenshot-aboutus-additional.png)

### Video Tour
- the daily mail did a news story on the plant collection, and an Iframe has been added here to link to that page.
- in future, a home-made video could be put in place of this one.

![About us video](/assets/readme-images/screenshot-aboutus-video.png)

### coffee section

-this section goes into more detail about the coffee, where it is sourced, and food menu items.

![About us Coffee](/assets/readme-images/screenshot-aboutus-coffee.png)

### plant section

- this section goes into more detail about the plants that are stocked.
- this section also contains useful plant care tips.

![About us Plants](/assets/readme-images/screenshot-aboutus-plants.png)

## Events page features

- the events page very simply displays upcoming events and dates.
- the events page will display No events if nothing is coming up.

![Events](/assets/readme-images/screenshot-events.png)

## Contact Us Page Features

### mailing list form

- this is a form for the user to fill out to be added to the Plnnt collection mailing list to receive updates.
- the data is sent to plant collection via email, but a back-end database needs setting up to be able to save this information in a future.

![Mailing list form](/assets/readme-images/screenshot-signup.png)

### Google Maps

- this shows the user how to get to the Plant collection from their location.

![google map](/assets/readme-images/screenshot-contact-map.png)

## Features still to add

### Reviews

- adding static reviews would need constant updating, in the future, adding reviews from the Google reviews API might add to the site.

### Mailing List

- currently the data from the contact us form is sent to Codeistite formdump to prove that it works; in the future, sending this to a database or email collection app would be preferable so the website owners can set up a mailing list.

### Fonts
- Adding HeroinePro and Aliana fonts to the website, as discussed with the owners, would be a good addition. I have had issues with the fonts causing page shift, and therefore, if I had more time on the project, I could fix this issue.

### JS for nav bar
- the nav bar works; however, in the future, using JS for the pop-up might be beneficial.

## Testing

### Validator Testing

- #### HTML

  - ##### Home page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2F)

    - no errors or warnings were found.

  - ##### About us page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Faboutus.html)

    - no errors or warnings were found.

  - ##### Events page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Fevents.html)

    - no errors or warnings were found.

  - ##### Contact us page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Fcontactus.html)
    - no errors or warnings were found.

- #### CSS

  - ##### Css for all pages [W3S Style sheet](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - no errors or warnings were found.

- #### Accessibility
  - Acessibility passed the lighthouse testing and achieved a score of 100%.
  - [lighthousescore](/assets/readme-images/screenshot-lighthouse.png)

### Form Testing

- the form has been tested to see if it submits the right data and if all the data is required to actually submit the form.
- the form was posted to [code institute form dump](https://formdump.codeinstitute.net/) where the data can be sent.

### Links Testing

- links have all been manually tested on each browser to make sure that they are all working and going to the correct address.

### Browser Testing

- manual testing has been done on chrome,safari,edge and Firefox, and no errors or bugs have been found.

### Device Testing

- [Am I Responsive](https://ui.dev/amiresponsive?url=https://ethantrout.github.io/The-Plant-Collection/)

### Friends and Business Owners: User Testing

- i took the website into the coffee shop to get the owners to user test it and give feedback on any changes that they would want.
- the owners gave me some written content to add to the page as well as images from the shop to add.
- [Owners Email](/assets/readme-images/screenshot-email-from-owners.png)

- i asked some friends to try out the site to find any bugs or issues with the user experience.

## Bug Fixes

### Responsive img sizes

Images were getting very warped in between medium and small screen sizes right before the breakpoint to change the grid to a single column layout. I realised that the breakpoint was too small and needed to be increased.

I also decided to set the display for one of the images on the landing page to zero on small screens, as having a two image hero that you have to scroll through wasn't very intuitive to users.

### Nav bar title breaking out

The nav bar title on very small screens (<600 width) was breaking out onto the hero. I first tried reducing the font size, but this didn't look good, so I decided to remove the title and display the drop down in the center. This works because the main picture left on the hero is the title of the business in their logo.

### .container

I tried using CSS properties with the min function in order to make it more readable.

```Css

.container {
    position: relative;
    --max-width: 1250px;
    --vertical-padding: 1rem;

    width: min(var(--max-width), 100% - (var(--vertical-padding)*2));
    margin-inline: auto;
    padding: var(--vertical-padding);

}

```

The CSS validator didn't like using variables within a calculation, so I have hard
coded the values.

```Css

.container {
   position: relative;
   /* --max-width: 1250px;
   --vertical-padding: 1rem; */

   width: min(1250px, 100% - 2rem);
   margin-inline: auto;
   padding: 1rem;

}

```

## Technologies Used

### Languages

- HTML5
- CSS

### Frameworks - Libraries - Programs Used

- [Am I Responsive](http://ami.responsivedesign.is/) -
- [Responsinator](http://www.responsinator.com/) -
- [Balsamiq](https://balsamiq.com/) -
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) -
- [Font Awesome](https://fontawesome.com/) -
- [GitHub](https://github.com/) -
- [Google Fonts](https://fonts.google.com/) -
- [TinyPNG](https://tinypng.com/) -
- [W3C](https://www.w3.org/) -
- PhotoShop - used to edit the site images.

### IDE
- at first, I was using Codeanywhere to edit and test code. The software is a very good code environment; however, due to server issues, I had to move to VScode for a portion of the project and work from a different branch because of permissions.

### Media

- all media used was provided by the owners of the shop and their visual artists.

### Resources used

- inspiration for CSS only nav bar [Youtube tutorial](https://www.youtube.com/watch?v=qKqLMlBKHlE)
- tutorials on CSS variables [Kevin powell youtube](https://www.youtube.com/@KevinPowell)
- [Stack Overflow](https://stackoverflow.com/)
- CSS reset [Reset](http://piccalil.li/blog/a-more-modern-css-reset/)
