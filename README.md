# The Plant Collection

The Plant Collection is a charming local destination nestled in Leeds, blending the pleasures of a cozy coffee shop with the vibrant allure of a plant haven. Our website is thoughtfully crafted to offer visitors an immersive glimpse into the essence of our business, inviting them to discover the unique fusion of coffee culture and botanical delights that sets us apart

![](/assets/images/responsiveUI.png)

## intro

The plant Collection already have a good presence on social media but they want a central hub for customers to undertsand why there coffee shop is diffrrent from others.

#### The main goals of this website for the site owner are:

        - Attract customers to the shop.
        - Give an overview of the buiness.
        - Show customers where it is and when it is open.
        - Allow repeat customers to see new menu items.
        - allow repeat customers to see what events are on.
        - create a website that is able to be easily edited by a future dev

## User Experience (UX)

- ### User stories

  - #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        3. As a First Time Visitor, I want to find where the shop is located and the opening times.

  - #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find information about the new food a coffee avalible.
        2. As a Returning Visitor, I want to be able to added to a mailing list to recieve updates on the shop.
        3. As a Returning Visitor, I want to find out what events are hapenning.

  - #### Frequent User Goals

        1. As a Frequent User, I want to check to see if there are any newly added menu items.
        2. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

- ### Design

  - #### Colour Scheme

        - The page will use a dark green and lighter version mainly thoughout the page. a secondary cream colour will be used as highlight. these are the Plant collections color scheme they use with the business.

  - #### imagery
    - imagery is very imporant for this business as one of the main drivers of what makes this coffee shop different is that the the look and style of the business.
    - all images will be taken from the business as the propperly portray the aesthetic of the shop.

- #### font
- the font Heroinepro should be used for all titles and Aliana for all other text. this has been expressed by the owners as it fits there online presence and imagery.

![Fonts](/assets/readme-images/Screenshot-fonts.png)

i have had issues with getting these fonts to work on the website. this could be a future feature to add. 


- ### Wireframes
<details>

 <summary>Desktop Wireframe</summary>

![Desktop Wireframe](/assets/readme-images/desktop-writeframe.png)

 </details>

 <details>
    <summary>Mobile Wireframe</summary>

![Mobile Wireframe](/assets/readme-images/mobile-wireframe.png)

 </details>

orginally the hero was going to be one image but the two image hero fits better with the two column layout of the desktop site,one image is used when on mobile.

The reviews section was removed as per disscused with the site owner as they wish to later have the reviews be the most recent reviews using the google reviews API- this could be a feature later added.

## Features

### scale and editing for futute devs

To improve load times as the website is it is only small i didnt use bootstrap, i created my own CSS utilities library and CSS variables for devs to quickly change the style or add new content.

#### CSS variables

There are variables for the main Color theme of the page which can be quickly changed from the variables.

- primary-clr
- primary-clr-light
- primary-clr-dark
- secondary-clr
- accent-clr

- ff
  the family font of all text can be changed using this.

there are also variables for font weight and size, these have been using with various heading and body text utilities simillarly named

- fw-normal
- fw-medium
- fw-bold

- fs-heading
- fs-subheading
- fs-emphisised-body
- fs-body
- size-(200-900)

  these can be changed with a media query if diferent font sizes need to be used on a smaller screen.

#### Css utilities

these follow the same naming convention but i will explain any differences here

- color-(primary,secondary,accent)
  this changes the text color

- bg-color-()
  this changes background color
- padding-block-(400-900)
  this will apply all around padding to elements

- container
  this is a general container for content on the page and gives automatic margin to anything within it.

  This has two local variables that can be changed to quickly change the amount of margin on all content using .container

  - LV max-with
  - LV vertical-padding

- button
  general styling for any button or link with hover effects

- even-columns
  this is used to set an even grid of elements. the site generally uses a two column layout but 3 is also used on some sections.

  this will break into one column layout on mobile.

## Home page features

### Navigation

- The navigation is at the top of the page and allows a user to quickly acess links to Home, About us, Events and contact us pages.
- The navigation highlights what page the user is on
- When on small mobile devices the large title willnot be displayed to make the UI less cluttered.

![Nav Bar](/assets/readme-images/Screenshot-navbar.png)

### The landing page

- the landing page includes the businesses logo and location aswell as a hand drawn image of the shop to draw the user in while keeping with the minimilist style of the business and the page.
- The drawn picture will not be displayed on very small screens as this allows mobile users to quickly get to the infomation they are looking for.

![Hero](/assets/readme-images/Screenshot-hero.png)

### The About section

- the about me includes a large title "Who are we" and a picture of the owner inside the shop in a two page collumn on desktop. highligting the main draw of the shop that it is a local business with someone who really cares about it in charge.
- it also includes a quote taken from the owner about the conception of the business and what the shop aims to be.

![About us](/assets/readme-images/Screenshot-whoarewe.png)

### featured section

The Plant collection dont sell the same products all year round and have specials on certain products that will only be in for limited time

- this section features a one column layout on desktop highlighting the product.

- the image draws a customer to seeing a highlihted product that the business is selling that week with a description of the product underneath.

![Featured](/assets/readme-images/Screenshot-featured.png)

### Coffee, Plants and Local

- these sections all display the 3 different aspects of the business and go more into detail about each one
- a image is included the highlight the difference of each one
- a link is included at the bottom that will send them to the larger section on each aspect on the about me page.

![Sections](/assets/readme-images/Screenshot-section.png)

### location and opening times section

- this section includes key infomation on where the shop is located, when it is open and what the business sells.

![Location](/assets/readme-images/Screenshot-location.png)

### footer

- the footer displays links to social media account of the plant collection
- it also displays a sign up for an emailing list

![footer](/assets/readme-images/Screenshot-footer.png)

## About page features

### Hero section

-this section gives a over view of the businesses aims and culture.
-it contains a img of the owners giving a face to the business

![About us hero](/assets/readme-images/Screenshot-about-hero.png)

### coffee section

-this section goes into more detail about the coffee, where it is sourced andfood menu items.

![About us hero](/assets/readme-images/Screenshot-about-coffee.png)

### plant section

- this section foes into more detail about the plants that are stocked
- this section also contains useful plant care tips

![About us hero](/assets/readme-images/Screenshot-about-plants.png)

## Events page features

- the events page very simply displays upcoming events and dates
- the events page will display No events if nothing is coming up

![About us hero](/assets/readme-images/Screenshot-events.png)

## Contact us page features

### mailing list form

- this is a form for the user to fill out to be added to the Plnnt collection mailing list to recieve updates
- the data is sent to plant collection via email but a Back end database needs setting up to be able to save this infomation in a future

![Mailing list form](/assets/readme-images/Screenshot-contact.png)

### Google map

-this shows the user how to get to the Plant collection from there location

![google map](/assets/readme-images/Screenshot-contact-map.png)

## Features still to add

### Reviews

- adding static reviews would need constant updating, in future adding reviews from the Google reviews API might add to the site.

### Mailing List

- currently the data from the contact us form is sent to Codeistite formdump to prove that it works, in future sending this to a database or email collection app would be preferable so the website owners can set up a mailing list.


### Fonts 
- Adding HeroinePro and Aliana font to the website as discussed with the owners would be good to add. I have had issues with the fonts causing page shift and therefore if i had more time on the project i could fix this issue

### JS for nav bar 
- the nav bar works however in a future addition using JS for the pop up might be benefical.

## Testing

### Validator Testing

- #### HTML

  - ##### Home page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2F)

    - no errors or warnings were found

  - ##### About us page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Faboutus.html)

    - no errors or warnings were found

  - ##### Events page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Fevents.html)

    - no errors or warnings were found

  - ##### Contact us page [W3S Homepage Html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Fcontactus.html)
    - no errors or warnings were found

- #### CSS

  - ##### Css for all pages [W3S Style sheet](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fethantrout.github.io%2FThe-Plant-Collection%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
    - no errors or warnings were found

- #### Accessibility
  - Acessibility passes the lighthouse testing and acheived a score of 100%
  - [lighthousescore](/assets/readme-images/Screenshot-lighthouse.png)

### Form Testing

- the form has been tested to see if it submits the right data and that all the data is required to actually submit the form.
- the form was posted to [code institute form dump](https://formdump.codeinstitute.net/) where the data can be senn

### Links Testing

- links have all been manually tested on each browers to make sure that they are all working and going to the correct address

### Browser Testing

- manual testing has been done on chrome,safari,edge and firefox and no errors or bugs have been found

### Device Testing

- [Am I Responsive](https://ui.dev/amiresponsive?url=https://ethantrout.github.io/The-Plant-Collection/)

### Friends and Business owner User Testing

- i took the website into the coffee shop to get the owners to user test it and give feedback on any changes that they would want.
  - the owners gave me some written content to add to the page aswell as images from the shop to add 
  - [Owners Email](/assets/readme-images/Screenshot-email-from-owners.png)

- i asked some friends to try out the site to find any bugs or issues with user experience

## bug Fixes

### Responsive img sizes

Images were getting very warped at in between medium to small screen sizes right before the breakpoint to change the grid to single column layout. i realised that the breakpoint was too small and needed to be increased.

i also decided to set the display for one of the images on the landing page to zero on small screens as having a two image hero that you have to scroll through wasnt very intuative to users.

### Nav bar title breaking out

The nav bar title on very small screens (<600 width) was breaking out onto the hero. i first tried reducing the font size but this didnt look good so i decided to remove the title and display the drop down in the center. This works as the main picture left on the hero is the Title of the business in there logo.

### .container

i tried using CSS properties with the min function in order to make it more readable.

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

the CSS validator didnt like using the variables within a calculation so i have hard
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
- PhotoShop - Used to edit the site images

### IDE
- at first i was using Codeanywhere to edit and test code. the software it a very good code enviroment however due to server issues, i had to move to VScode for a portion of the project and work from a different branch because of permissions. 

### Media

- all media used was given by the owners of the shop and there visual artist.

### Resources used

- inspiration for CSS only nav bar [Youtube tutorial](https://www.youtube.com/watch?v=qKqLMlBKHlE)
- tutorials on CSS variables [Kevin powell youtube](https://www.youtube.com/@KevinPowell)
- [Stack Overflow](https://stackoverflow.com/)
- CSS reset [Reset](http://piccalil.li/blog/a-more-modern-css-reset/)
