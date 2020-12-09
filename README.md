# Cartel Coffee Website Build

## Overview

The purpose of this project is to build a mobile responsive website for a new coffee shop in Dublin called Cartel coffee. The Business wants to increase their online visibility, increase revenue and to attract new customers. They want to introduce the ability to receive takeaway orders and start selling online. They want to use the site as a platform to update customers on business changes and to continue trading if restaurants are forced to close during Covid-19 restrictions. 
The goal is to build a mobile first site which meets the intial business needs while providing an excellent user experience for site users. I also aim to create a platform that can be built upon to meet the business's ongoing business needs.

**NB:** *This is a theoretical business created for educational purposes only*

## UX
 
The intention of this site is to allow new and existing users to find the business, learn about the business and to convert into physical customers at the business's location or virtual customers via ordering online, over the phone and by email. 
To provide a great user experience it is important that infomration is displayed clearly in a logical order of importance. As this website is designed to provide several distinct functions (contact, buy, order and inform), for a broad range of users, emphasis has been made to create many interlinking ways for customers to find and source the information that is relevant to them while ignoring information that may not be relevant at that moment. 
To increase brand awareness and a consistent experience for online and offline customers, the website has been designed to mirror the styling and motif that customers experience while visiting the business's physical location. 

### Strategy

#### User goals
* Users want to learn more about the business
* Users want to view the business's menus
* Users want to make orders for takeaway/collection
* Users want to view the reservations policy and make a booking/reservation
* Users want to shop for coffee, equipment and merchandise online
* Users want to contact the shop for more information
* Users want to visit the business's social media profiles to learn more about them

#### Business Needs
* The business owner wants to increase their online awareness and to interact with new and existing customers online
* The business owner wants to increase revenues by attracting new customers who are searching for local businesses online
* The business owner wants to increase their brand awareness by providing background information about the business and it's staff
* The business owner wants to prequalify customers and speed up how customers order in store by displaying their menus online
* The business owner wants to allow takeaway orders by displaying their menu and contact information online
* The business owner wants to receive more reservations by providing customers with their booking policy and contact information online
* The business owner wants to engage existing customers by displaying their "specials board"
* The business wants to increase revenues by offering coffee, subscriptions, equipment and merchandise for sale online
* The business owner wants to increase social media interaction with customers by linking their social media accounts on their websites

#### User Stories

##### Basic user stories
1. Daniel needs to see the menu and phone number so he can order for collection.
2. Lisa needs to fill out a contact form so that she can make a reservation for lunch.
3. Marius wants to view the stores's product range and contact details so he can order products remotely. 
4. Paul wants to view a gallery of the Cafe and their social media, so he can decide if it is an appropriate environment to hold a business meeting.

##### Detailed user stories
1. Daniel is a 45 year old businessman who works in the area. He's looking for a coffee shop that's close to his work, where he can get his morning coffee, grab lunch or hold casual business meetings at short notice. He needs to find the business location, view their menu, see if they have wifi and view their social media to see if there's enough seating to hold a business meeting.
2. Lisa is a 21 year old student who wants to find somewhere nice for a first date. She wants to view images of the cafe as she wants to impress her date with somewhere nice. She also want's to view the menu, prices (shes a student afterall) and to make a reservation so they don't have to wait akwardly when they arrive. 
3. Marius is an elderly gentleman living abroad who wants to buy a christmas present for his coffee loving son who lives locally. He wants to view coffee and brewing equipment and to make an order over the phone for delivery to his sons address. 
4. Melissa is a regular customer who wants to see if the shop is still open during the latest lockdown restrictions. She also wants to order some coffee beans as she's working from home and want's to have coffee for days when she can't make it to the shop. 
5. Paul is working from home and is looking for somewhere to get lunch. He wants to view the menu and to make an order for collection in advance as he only has an hour for lunch. 

### Scope 

#### Features to be included in initial iteration
* Display prominent logo
* Navbar for navigation amongst pages and sections
* Display business contact information
* Display Business location & map
* Display Business menu
* Display Products & Product information
* Provide Business social media links
* Provide terms and conditions
* Provide privacy policy
* Create a means to navigate between pages

#### Features/Functionality to be added
* Add products to basket
* Checkout and purchase products online
* Order food online functionality
* Detailed menu item information on hover - Allow a detailed description of the menu food item on click or hover.
* Contact box in contact.html page to link to preffered email address.
* Individual product pages - A specific detailed .html page with full product information for each product in the shop.
* Build out privacy policy & Terms and conditions pages - These footer links are here as placeholders only to display that these are important links to dislay on a consumer facing site. As this is a "Mock business" these have been left blank but if this were to be used a detailed privacy policy would be created to build customer confidence and adhere to european regulations. 

### Structure 

* **index.html:** The Primary landing page for the site which includes the key information on the business and links to additional pages where more detailed information can be found.
* **contact.html:** This is the primary contact page, where the business's contact information can be found so that potential customers can contact the business and convert into customers by making bookings, visiting the store, phoning, making email contact etc...
* **menu.html:** This page describes the cafe's food and drink menu, as this is the business primary function it is imperative to clearly display their menu items so that customers can order remotely or make the decision to dine in-store
* **shop.html:** This page displays the customers "take home" product range of coffee, equipments and merchandise. This enables the business to explore additional revenues from existing customers and to reach a new target audience who may not be able to visit their store to shop.
* **about.html:** This page displays supporting information on the business. It's purpose is to build brand awareness, consumer confidence and trust in the business. 

#### Detailed Features

* Homepage
 * Navigation - allows users to navigate between pages and sections of the site by linking relevant pages in the header of each page. Bootstraps navbar collapse is used to create a clean and condensed experiece on smaler screen sizes.
 * hero image slider - allows users to see and access important information at the top of the page. Carousel slider is used to display multiple images clearly accross all device sizes.
 * Welcome text - allows users to quickly learn about the business background to build trust in the business and to encourage them to explore more on the site
 * Menu section - allows users quick access to the restaurants food and beverage menus so they can order food to collect 
 * Shop categories section - allow users to quickly access the primary shop categories in the online shop so they can purchase coffee beans and other items
 * Shop button - gives users a quick way to access the entire shop page in case they do not wish to shop by one of the categories above. By clicking each button they are linked to their elected category on the shop.html page.
 * Footer - provides links to popular pages and contact information to allow users to navigate to additional site pages when scrolling down the page without having to scroll back to the main nav at the top of the page.

* About page
 * Navigation - a consistent navigation bar allows users to easily navigate to the different site pages without having to use their browser back/forward buttons.
 * About intro section - provides background information on the business to build rapport and trust with new users in order to encourage them to make a purchase or to visit the cafe. 
 * meet the team section - introduces the team members to users to build trust and a sense of personality to encourage users to make a booking or purchase.
 * footer - provides links to popular pages and contact information to allow users to navigate to additional site pages when scrolling down the page without having to scroll back to the main nav at the top of the page.


* Contact page/Reservation page
 * Navigation - a consistent navigation bar allows users to easily navigate to the different site pages without having to use their browser back/forward buttons
 * Google maps embedded map - allows users to see stores physical location and click link to open in preferred map application so they can navigate easily to the cafe
 * Phone number - displays phone number with supporting icon so users can quickly call the cafe to make an order, reservation or other enquiry
 * Email address - displays the cafe's email address for users who wish to make an enquiry by email
 * contact form - allows customers to make an email enquiry without the need to open another tab or their email application. By entering their name, email address, phone number (optional) and their message users can contact the business with their enquiry. From validation ensures customers that ther enquiry has been submitted and notifies and prevents submission if a required field has been missed. 
 * footer - provides links to popular pages and contact information to allow users to navigate to additional site pages when scrolling down the page without having to scroll back to the main nav at the top of the page.


* Menu page
 * Navigation - a consistent navigation bar allows users to easily navigate to the different site pages without having to use their browser back/forward buttons
 * Coffee menu section
 * Food menu section
 * Dessert menu section
 * Order Button
 * footer - provides links to popular pages and contact information to allow users to navigate to additional site pages when scrolling down the page without having to scroll back to the main nav at the top of the page.


* Shop page
 * Navigation - a consistent navigation bar allows users to easily navigate to the different site pages without having to use their browser back/forward buttons
 * Category headings - Group relevant products together by association to increase readability sense of purpose for first time users.
 * Product tiles: Border, image thumbnail, tilte, price, buy button.
 * footer - provides links to popular pages and contact information to allow users to navigate to additional site pages when scrolling down the page without having to scroll back to the main nav at the top of the page.

### Skeleton

1. **Main Navigation:** A consistent top nav bar is present across all site pages to allow navigation through various pages.
2. **Footer navigation:** A consistent bottom footer contains and reinforces importance of main navigation links present in main navbar. This aids navigation to next point of interest once a user has scrolled down the page.
   links have been chosen specifically to aid conversion with call to action for contact, social media interaction, shop, make a reservation or order from menu. 
   Additional links such as about, privacy polics anf T&Cs have been added to footer as they are important but do not merit inclusion in main navbar. 
3. **Images:** Images and Image tiles are used to link strong visual images to relevant pages. Popular categories are represented as images and overlying text, hover functionality and highlighting are strategies used to reinforce that an image is a link. 
4. **IDs:** Id's have been used to allow quick navigation to specific points on a single webpage. This is designed to aid conversion by bringing the user directly to their point of interest without the potential to get distracted. 
   The use of Id based navigation also allows more distinct information to be condensed onto a fewer number of pages for a better user experience and a smaller site. 
5. **Buttons:** Buttons are used for reinforce form submission or to create a strong emphasis that a link to anothere page or information is present. 

#### Wireframes

![index.html wireframe](assets/wireframes/wireframeindexdesktop1.png)

![index.html wireframe](assets/wireframes/wireframeindexmobile.png)

#### Mockups

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

### Surface

Fonts

Colors

Icons

Images


## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

### HTML5 

![HTML5 Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/120px-HTML5_logo_and_wordmark.svg.png): 

Is used to provide content and structure to the website.

### CSS3 

![CSS Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/120px-CSS3_logo_and_wordmark.svg.png):

Is used to add styling, structure, layout and design to the page and to increase accessibility to user across various devices. 

### Bootstrap V 4.5.3 

![Boootstrap logo](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/220px-Bootstrap_logo.svg.png)

Is used to add structure, layout and mobile first design to webpages. 

## Code 

### Bugs 

#### Bugs Fixed

* Bug: Navbar toggle burger stack stacking vertically on XS screensizes. 
  Fix: Added media query to navbar-brand so font-size shrinks on XS devices this left ample room for the burger stack icon and contact icons and prevented vertical stacking of Header items on XS devices.

* Bug: Margin or padding is creating indent in top right of Navbar and footer.
  Fix: Used view port width value to ensure that the navbar occupies the full width of the screen across all screen sizes. 

* Bug: Carousel images not scaling correctly when changing screensizes. 
  Fix: Added VH and VW values that matched those of the the images containing div. Added margins, object fit and position values to ensure images are cropped appropriately across various screensizes. 

* Bug: Labels for Tiles not scaling correctly when changing screensizes. On smaller screensizes the label headings were moving off their desired position in the center of the image tiles.
  Fix: Used position: relative and top and bottom %'s to fix the headings to the image tiles regardless of screensize. 

* Bug: Button placement on shop category homepage tiles not scaling correctly on mobile on IOS.
  Fix: Use position absolute and top positon 50% to position button relative to containing parent

* Bug: Footer Li items offset and displaying content out of screen.
  Fix: Removed default left padding on unordered lists to ensure desired content spacing for footer list items.

* Bug: Reoccuring Right indent on body content causing alignment issues.
  Fix: Remove right margin on container-fluid class that was causing alignment issues across site.

#### Remaining Bugs To Be Fixed

* Bug: Footer content overlapping on smaller screen sizes. Third column is hidden on small screensizes and other column items were not occupying the space left behind. 
  Fix: Used bootstrap flex and justify-content properties to control how content is aligned across screensizes. 

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- To fix issues with footer content alignment I read documentation on flexbox at [This article](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container)
  I confirmed how to implement flexbox utilities while using Bootstrap by reading the documentation on [this page](https://getbootstrap.com/docs/4.5/utilities/flex/)

- To create a more understandable submenu functionality for the submenu on the menu.html page I used a scroll functionality that I learnt about in [this post](https://stackoverflow.com/questions/24739126/scroll-to-a-specific-element-using-html)
### Code 
- As an alternate method to add background opacity I used a method I found published by [Andy Hattemer and Nicholas Cerminara](https://www.digitalocean.com/community/tutorials/how-to-change-a-css-background-images-opacity)

- Inspiration for animation used in menu.html subnav was from [this stack overflow discussion](https://stackoverflow.com/questions/42745506/how-to-make-an-icon-spin-with-i-tag-in-html5-through-css3) and general animation info was found at [this page](https://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp)

### Media
- The photos used in this site were obtained from ...

Image credit: Roman Bozhko ![two bikes in coffee shop](https://images.unsplash.com/photo-1493857671505-72967e2e2760?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80)
Photo by [Roman Bozhko](https://unsplash.com/@romanbozhko?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/coffee-shop?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

Image credit: earlybird coffee ![early bird coffee beans package](https://images.unsplash.com/photo-1599639957043-f3aa5c986398?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1279&q=80) 
Photo by [earlybird coffee](https://unsplash.com/@earlybird_coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

<span>Photo by <a href="https://unsplash.com/@mensroom?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Mike Marquez</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@eaterscollective?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Eaters Collective</a> on <a href="https://unsplash.com/s/photos/sandwiches?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@aidasolomon?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Aida Solomon</a> on <a href="https://unsplash.com/s/photos/sandwiches?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@moniqa?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Monika Grabkowska</a> on <a href="https://unsplash.com/s/photos/croissant?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@kfred?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Karl Fredrickson</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@sevcovic23?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Petr Sevcovic</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@nate_dumlao?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Nathan Dumlao</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@jtylernix?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Tyler Nix</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@jonforson?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">John Forson</a> on <a href="https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@tofansilviuben?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Silviu Beniamin Tofan</a> on <a href="https://unsplash.com/s/photos/coffee-package?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

<span>Photo by <a href="https://unsplash.com/@camille1030?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Camille Chen</a> on <a href="https://unsplash.com/s/photos/croissants?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

Menu Background
<span>Photo by <a href="https://unsplash.com/@abhaysanthosh007?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Abhay Santhosh</a> on <a href="https://unsplash.com/s/photos/palm-tree-graphic?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

Contact Background
<span>Photo by <a href="https://unsplash.com/@cyzx?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Clifford</a> on <a href="https://unsplash.com/s/photos/old-chairs?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

### Acknowledgements

- I received inspiration for this project from Xj
