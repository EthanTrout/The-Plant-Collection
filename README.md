# The Plant Collection

The Plant Collection is a charming local destination nestled in Leeds, blending the pleasures of a cozy coffee shop with the vibrant allure of a plant haven. Our website is thoughtfully crafted to offer visitors an immersive glimpse into the essence of our business, inviting them to discover the unique fusion of coffee culture and botanical delights that sets us apart

## intro

The plant Collection already have a good presence on social media but they want a central hub for customers to undertsand why there coffee shop is diffrrent from others.

#### The main goals of this website are:

- Attract customers to the shop.
- Give an overview of the buiness.
- Show customers where it is and when it is open.
- Allow repeat customers to see new menu items.
- allow repeat customers to see what events are on.

## User Experience (UX)

- ### User stories

  - #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the organisation.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        3. As a First Time Visitor, I want to find where the shop is located and the opening times.

  - #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find information about the new food a coffee avalible.
        2. As a Returning Visitor, I want to be able to added to a miling list to recieve updates on the shop.
        3. As a Returning Visitor, I want to find out what events are hapenning.

  - #### Frequent User Goals

        1. As a Frequent User, I want to check to see if there are any newly added menu items.
        2. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

- ### Design

  - #### Colour Scheme
    - The page will use a dark green and lighter version mainly thoughout the page. a secondary cream colour will be used as highlight

- ### Wireframes

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

### Navigation 
- The navigation 


### The landing page 
- the landing page includes the businesses logo and location aswell as a hand drawn image of the shop to draw the user in while keeping with the minimilist style of the business and the page.

### The About section 
- the about me includes a large title "Who are we" and a picture of the owner inside the shop in a two page collumn on desktop. highligting the main draw of the shop that it is a local business with someone who really cares about it in charge.
  
- it also includes a quote taken from the owner about the conception of the business and what the shop aims to be.

### featured section 
The Plant collection dont sell the same products all year round and have specials on certain products that will only be in for limited time 

- this section features a one column layout on desktop highlighting the product. 

- the image draws a customer to seeing a highlihted product that the business is selling that week with a description of the product underneath.

### Coffee, Plants and Local
- these sections all display the 3 different aspects of the business and go more into detail about each one
  
- a image is included the highlight the difference of each one 
- a link is included at the bottom that will send them to the larger section on each aspect on the about me page.

### location and opening times section 
- this section includes key infomation on where the shop is located, when it is open and what the business sells.

### footer 
- the footer displays links to social media account of the plant collection 
- it also displays a sign up for an emailing list 