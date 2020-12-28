# Cartel Coffee Website Build

## Overview

The purpose of this project is to build a mobile responsive website for a new coffee shop in Dublin called Cartel coffee. The Business wants to increase their online visibility, increase revenue and to attract new customers. They want to introduce the ability to receive takeaway orders and start selling online. They want to use the site as a platform to update customers on business changes and to continue trading if restaurants are forced to close during Covid-19 restrictions. 
The goal is to build a mobile first site which meets the intial business needs while providing an excellent user experience for site users. 

**NB:** *This is a theoretical business created for educational purposes only*

## UX
 
The intention of this site is to allow new and existing users to find the business, learn about the business and to convert into physical customers at the business's location or virtual customers via ordering online, over the phone and by email. 
To provide a great user experience it is important that information is displayed clearly in a logical order of importance. As this website is designed to provide several distinct functions (contact, buy, order and inform), for a broad range of users, emphasis has been made to create multiple interlinking navigation methods so that customers can find and source the information that is relevant to them while ignoring information that may not be relevant at that moment. 
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
1. Daniel needs to see the menu and phone number so he can order foof for collection.
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
* A prominent logo
* A Navbar for navigation amongst pages and sections
* The business contact information
* The Business location & map
* A contact form
* A Booking form
* The Food & Drinks menus menu
* Products & Product information
* Business social media links
* Create a means to navigate between pages
* A list of commonly asked questions/FAQs
* A Covid-19 Alert

#### Features/Functionality to be added
* Functionality to add products to basket
* Functionality to checkout and purchase products online
* Functionality to order food online 
* Detailed food menu item information - Allow a detailed description of the menu food item on click or hover.
* A functioning contact box in contact.html page to link to preffered email address using PHP.
* Detailed  Product information - Allow a detailed description of each product on click or hover.
* Individual product pages - A specific detailed .html page with full product information for each product in the shop.
* Build out privacy policy & Terms and conditions pages - These footer links are here as placeholders only to display that these are important links to dislay on a consumer facing site. 
  As this is a "Mock business" these have been left blank but if this were to be used a detailed privacy policy and Terms & conditions page would be created to build customer confidence and adhere to european regulations. 

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
 * Intro Jumbotron - A brief intro text box explaining the purpose of the page and encouraging first-time learning.
 * Category headings - Group relevant products together by association to increase readability sense of purpose for first time users.
 * Product tiles: Border, image thumbnail, tilte, price, buy button. Clear, uniform product structure shows customers the key information needed to inform a purchase.
 * Merchandise Jumbotron - A prominent text box to explain new products are coming soon, to encourage customers to return to the site at a later date.
 * Footer - provides links to popular pages and contact information to allow users to navigate to additional site pages when scrolling down the page without having to scroll back to the main nav at the top of the page.

### Skeleton

1. **Main Navigation:** A consistent top nav bar is present across all site pages to allow navigation through various pages. 
    ![main nav screenshot](assets/images/readmeimgs/main_nav.png)
     Bootstrap navbar expand/collapse classes were used to improve user experience on mobile devices. 
    
    ![main nav collapse screenshot](assets/images/readmeimgs/navbar_collapse.png)
    
    I chose to align the navbar collapse icon and collapsed to the menu to the right as [research shows](https://www.livescience.com/what-causes-left-handedness.html) that 85% - 90% of users are right handed and right-alignment results in marginally easier use for right-handed users.
    The Active class is used highlight the current page.
    
2. **Footer navigation:** A consistent bottom footer contains and reinforces importance of main navigation links present in main navbar. This aids navigation to next point of interest once a user has scrolled down the page.
   The footer links listed have been chosen specifically to allow easy navigation to the key pages and page sections.
   Additional links such as the about page, privacy policies and T&Cs have been added to footer as they are important pages to include on the site but do not merit inclusion in main navbar. 

    ![footer nav screenshot](assets/images/readmeimgs/footer_nav.png) 

3. **Images as links:** Images and Image tiles are used throughout the site to link strong, descriptive visual images to relevant pages. Popular categories and shop categories are represented as image tiles and overlying text, hover functionality and highlighting are strategies used to reinforce that an image is a link. 
    ![navigation tile screenshot1](assets/images/readmeimgs/Menu_Buttons.png)
    ![navigation tile screenshot2](assets/images/readmeimgs/Shop_Buttons.png)

4. **Buttons:** Buttons are used for reinforce form submission or to create a strong emphasis that a link to another page or information is present. Consistent button coloring is used across site to drive home the functionality of buttons on the site. Clear button labelling is used to 
    encourage first-time learning and correct use of buttons on the site.
    ![Buttons navigation screenshot](assets/images/readmeimgs/Button_Styles.png)

5. **IDs as links:** Id's have been used to allow quick navigation to specific points on a single webpage. This is designed to aid conversion by bringing the user directly to their point of interest without the potential to get distracted. 
   The use of Id based navigation also allows more distinct information to be condensed onto a fewer number of pages for a better user experience, a more condensed site and faster page load times. The footer utilises several id's as links to specific sections
   on the menu, shop and contact pages.

6. **Secondary Navigation Bar:** A secondary navigation menu is utilised on the menu page to allow swift navigation to a user's desired menu section. 
    The secondary navigation menu uses a page specific color palette to reinforce it's specific association to the menu page. The submenu
    links to specific page section id's as outlined the the section above. 

#### Wireframes

[Home page](assets/wireframes/CC_Index.html_Wireframes.pdf)

[Menu page](assets/wireframes/CC_Menu.html_Wireframes.pdf)

[Contact page](assets/wireframes/CC_Contact.html_Wireframes.pdf)

[Shop page](assets/wireframes/CC_Shop.html_Wireframes.pdf)

#### Mockups

### Surface

#### Fonts ####
**General**
Sans-serif fonts have been chosen site-wide for a minimilistic style, consistent with the companies interior decor and to improve legibility for site users.
Font-size and line height are adjusted on different device sizes to ensure correct distribution of information and layout across all devices. Altering line height and text-padding on mobile devices 
aids navigation and touch-interaction on touch-screen devices.

**Logo & Title Fonts**
The Bebas Neue font is used for the company logo and the carousel image titles. It was chosed because of it's bold appearance and clear readability. This font has been styled to be uppercase with a heavier font-weight than the body text
to create recognisable branding and obvious visual impact for key site information.

**Body Fonts**
The Montserrat font was selected for the body text for it's slim, legible and professional appearance. A much lighter font-weight is used to reinforce an overall minimilistic style 
and to create contrast between branding text and headings. 

**Headings**
Headings also utilise the Montserrat font but are styled with a heavier font-weight to reinforce a higher priority of importance than accompanying body text.

**Additional Fonts**
The Sans-serif font has been chosen as a fallback font if chosen fonts cannot be loaded. 

#### Colors ####
Colors are used to increase contrast, visual impact, to indicate interactivity of elements and to improve readability across the site. 

**Navigation colors:** Dark, muted header and footer colors are used to give a sense of space and contrast to the main and footer navigation. 

**Body colors:** In contrast the body text utilises light, subtle background colors with dark text colors to clearly distinquish the page content from the navigation. 

**Call-to-action colors:** Buttons, Links and alerts utilise really bright vibrant colors to encourage click behaviour and to act as eyecatching visual indicators of primary call-to-action elements.

**Heading colors:** Bold colored headings clearly define where individual sections begin. Boldly colored section background colors contrasted with light fonts are chosen to clearly define the purpose of each section of information.

**Section Background colors:** Coloured sections with muted grey backgrounds are used to clearly distinguish relevant areas of information. This is important as page sections are scaled to width on larger screen-widths to keep information condensed and easily readable.

#### Icons ####
Icons are used as metaphors to reinforce meaning of key navigation elements. The paper plane icon is used to reinforce meaning of send/submission buttons, food and drink icons are used on the menu page to 
reinforce the sub-menu navigation buttons and Icons are used for the contact information and social media links to clearly apply meaning to text-heavy page sections like the footer.

#### Images ####
Images are used in several ways on the site. 

**Carousel Images:** Eye catching images are used on the homepage carousel to clearly indicate the businesses key activities. These are chosen to encourage users to understand the purpose of the business as soon as they land on the homepage.

**Homepage Image Tiles:** Appealing images are used as clickable tiles for the menus navigation links and shop navigation links on the homepage to quickly visually communicate the type of content a user will be brought to when clicking on each image tile. 

**Product images:** Studio images are used to clearly display a products purpose and to encourage users to buy. Clear striking product images are contrasted with plain backgrounds to put the emphasis on the product and to keep user focus on the key information on the page.

**Background-images:** Subtle background images with added opacity are used to give users a greater understanding of the business's style and appearance without drawing away from the key information on each page. These background images and colored divs are also used to break-up large areas of white-space
for a more visually appealing appearance and a more defined flow of information through the page. 

---

## Technologies Used

![HTML5 Logo](assets/images/technologies/html5.png)
### HTML5 
[https://www.w3.org/html/](https://www.w3.org/html/) 

Is used to add content, structure and the ability to navigate to the website.


![CSS Logo](assets/images/technologies/css3.png)
### CSS3
[https://www.w3.org/TR/CSS/](https://www.w3.org/TR/CSS/) 

Is used to add styles, layout, design and interactivity to the page and to increase usability to users across various devices. 


![Boootstrap logo](assets/images/technologies/bootstrap.png)
### Bootstrap V4.5.3 
[https://getbootstrap.com/](https://getbootstrap.com/) 

Is used to add structure, layout and mobile first responsive design to the webpages. 


![Gitpod Logo](assets/images/technologies/gitpod.png)
### Gitpod
[https://www.gitpod.io/](https://www.gitpod.io/) 

Is used to write, edit and preview code.


![Github](assets/images/technologies/github.png)
### GitHub 
[https://github.com/](https://github.com/)

Is used to host, share and deploy the project.


![Balsamiq Logo](assets/images/technologies/balsamiq.png)
### Balsamiq
[https://balsamiq.com/](https://balsamiq.com/)

Is used to create wireframes as visual mockups of the final site design

---

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

* Bug: Category heading overflow on tablet. ![cathead overflow bug](assets/images/bugs/h5 cathead overflow bug.png)
  fix: Add additional media query for max-width: 1000px 
* Bug: Button placement on shop category homepage tiles not scaling correctly on mobile on IOS.
  Fix: Use position absolute and top positon 50% to position button relative to containing parent

* Bug: Footer Li items offset and displaying content out of screen.
  Fix: Removed default left padding on unordered lists to ensure desired content spacing for footer list items.

* Bug: Reoccuring Right indent on body content causing alignment issues.
  Fix: Remove right margin on container-fluid class that was causing alignment issues across site.

* Bug: Modal on Shop page was fixed to the top of the page. When using the footer navigation links to navigate to popular shop categories (coffee, subscriptions, equipment and merchandise), the user would be scrolled down the page.
This meant that the modal was out of the viewport and customers could not interact with the shop page. 
  Fix: Using position: fixed, percentage top and left values and a transform value, I was able to ensure that the modal is position in the center of the screen even when the screen is scrolled. 
  The code used for this fix was taken from a CSS tricks article credited below. 

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
### Code 
- To fix issues with footer content alignment I read documentation on flexbox at [This article](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container)
  I confirmed how to implement flexbox utilities while using Bootstrap by reading the documentation on [this page](https://getbootstrap.com/docs/4.5/utilities/flex/)

- To create a more understandable submenu functionality for the submenu on the menu.html page I used a scroll functionality that I learnt about in [this post](https://stackoverflow.com/questions/24739126/scroll-to-a-specific-element-using-html)

- To vertically center the carousel caption text on the index.html page. I used the transform technique as described in [this forum](https://stackoverflow.com/questions/27279865/how-to-vertically-center-a-bootstrap-carousel-caption)
 from which I utilised this snippet of css:


        .carousel-caption{
        top: 50%;
        transform: translateY(-50%);
        bottom: initial;
        }

        .carousel-item{
        -webkit-transform-style: preserve-3d;
        -moz-transform-style: preserve-3d;
        transform-style: preserve-3d;
        }

- As an alternate method to add background opacity I used a method I found published by [Andy Hattemer and Nicholas Cerminara](https://www.digitalocean.com/community/tutorials/how-to-change-a-css-background-images-opacity)

- Inspiration for animation used in menu.html subnav was from [this stack overflow discussion](https://stackoverflow.com/questions/42745506/how-to-make-an-icon-spin-with-i-tag-in-html5-through-css3) and general animation info was found at [this page](https://www.w3schools.com/cssref/css3_pr_animation-keyframes.asp)

- To find a way to hide the homepage menu tile headings, I was inspired by a method described in [this stackoverflow article](https://stackoverflow.com/questions/9913293/change-text-on-hover-then-return-to-the-previous-text/9913526)

- To enable modals to appear upon page load by default I found a solution at [this article](https://www.tutorialrepublic.com/faq/how-to-launch-bootstrap-modal-on-page-load.php#:~:text=Answer%3A%20Use%20the%20Bootstrap%20.,modal('show')%20method&text=modal('show')%20method%20for%20launching%20the%20modal%20window,to%20subscribe%20the%20website%20newsletter.)
 I edited this simple script 
 
- To apply favourable modal positioning I used a technique described in [this article](https://css-tricks.com/considerations-styling-modal/)
    from which I utilised this snippet of code 
    
        .modal {
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        }

### Media
- The photos used in this site were obtained from 

[Carousel 1 Image](https://images.unsplash.com/photo-1493857671505-72967e2e2760?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80)
[Photo by Roman Bozhko](https://unsplash.com/@romanbozhko?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [ on unsplash](https://unsplash.com/s/photos/coffee-shop?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Carousel Image 2](https://unsplash.com/photos/qE1jxYXiwOA)
[Photo by Petr Sevcovic](https://unsplash.com/@sevcovic23?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[carousel 3 image: unused](https://unsplash.com/photos/kQIaF3iPLS4)
[Photo by Goran Ivos](https://unsplash.com/@goran_ivos?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [On unsplash](https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[carousel 4 image](https://unsplash.com/photos/pf70wY3llLg)
[Photo by Kadir Celep](https://unsplash.com/@kadircelep?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)[ on unsplash](https://unsplash.com/s/photos/coffee-grinder?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Espresso Tile](https://unsplash.com/photos/LnG_bBDHLYo)
[Photo by Lodewijk Hertog](https://unsplash.com/@lue101?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [On unsplash](https://unsplash.com/s/photos/espresso?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Porridge tile](https://unsplash.com/photos/ZgfMmFGGf-E)
[Photo by Chris Ralston](https://unsplash.com/@thisisralston?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText0) [On Unsplash](https://unsplash.com/s/photos/avocado-toast?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Sandwich homepage tile](https://unsplash.com/photos/pLKgCsBOiw4)
[Photo by Eaters Collective](https://unsplash.com/@eaterscollective?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/sandwiches?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Croissant homepage tile](https://unsplash.com/photos/eAsck4oAguM)
[Photo by Monika Grabkowska](https://unsplash.com/@moniqa?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText") [on unsplash](https://unsplash.com/s/photos/croissant?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[croissant 2](https://unsplash.com/photos/wkBbTvRm9K0)
[Photo by Fiona Smallwood](https://unsplash.com/@thepeoplesdigital?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)[On unsplash](https://unsplash.com/s/photos/croissant?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Croissant 3](https://unsplash.com/photos/CsmbYXwHJus)
<span>Photo by <a href="https://unsplash.com/@sarahcreates?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">SarahCreates</a> on <a href="https://unsplash.com/s/photos/croissant?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

[coffee on stool](https://unsplash.com/photos/tA90pRfL2gM) not used
[Photo by Nathan Dumlao](https://unsplash.com/@nate_dumlao?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[la marzocco](https://unsplash.com/photos/Jfqv2YJZ0y0) not used
[Photo by Tyler Nix](https://unsplash.com/@jtylernix?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Pourover](https://unsplash.com/photos/WWzDPKot6nQ)
[Photo by John Forson](https://unsplash.com/@jonforson?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Coffee Tile](https://unsplash.com/photos/aQlSRcKHIfA)
[Photo by Silviu Beniamin Tofan](https://unsplash.com/@tofansilviuben?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/coffee-package?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Merchandise mug](https://unsplash.com/photos/kBJEJqWNtNY)
[Photo by Ryan Riggins](https://unsplash.com/@ryan_riggins?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [On unsplash](https://unsplash.com/s/photos/enamel-mug?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Menu Background](https://unsplash.com/photos/PG5G-h9rThU)
[Photo by Abhay Santhosh](https://unsplash.com/@abhaysanthosh007?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/palm-tree-graphic?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Contact Background](https://unsplash.com/photos/VobvKmG-StA)
[Photo by Clifford](9https://unsplash.com/@cyzx?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [on unsplash](https://unsplash.com/s/photos/old-chairs?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Coffee beans product Image](https://images.unsplash.com/photo-1599639957043-f3aa5c986398?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1279&q=80) 
[Photo by earlybird coffee](https://unsplash.com/@earlybird_coffee?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) [On unsplash](https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

[Chemex product Picture](https://store.chemexcoffeemaker.com/media/catalog/product/c/h/chemex-classic-6cup-detail_1.png)
[Sourced from](https://www.chemexcoffeemaker.com/six-cup-classic-series-coffeemaker.html)

[Hario V60 Dripper Product Picture](https://cdn.shopify.com/s/files/1/0065/2718/9028/products/VDG-01B_8fca3194-807a-4835-8619-c1ffeda11367_900x.jpg?v=1570060789)
[Sourced from](https://www.hario.co.uk/collections/hario-v60-coffee-drippers/products/hario-v60-glass-coffee-dripper-black-01)

[Aeropress Product Picture](https://aeropress.com/wp-content/uploads/2020/01/AeroPress-Original-red.jpg)
[Sourced from](https://aeropress.com/product/aeropress-coffee-maker/)

[Rancillio Coffee Maker](https://www.ranciliogroup.com/app/uploads/2019/09/ranciliogroup-silviapro-equipment-1080x1080-1.jpg)
[Sourced from](https://www.ranciliogroup.com/rancilio/silvia-pro/)

HTML5 Logo: 
[W3.org](https://www.w3.org/html/logo/#downloads)

CSS3 Logo:
[wikipedia commons](https://commons.wikimedia.org/wiki/File:CSS3_logo_and_wordmark.svg)

Bootstrap Logo:
[Wikipedia](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework))

Gitpod Logo:
[Gitpod](https://www.gitpod.io/media-kit/)

Github Logo:
[Github](https://github.com/logos)

Balsamiq Logo:
[Balsamiq](https://balsamiq.com/company/brandassets/)

### Acknowledgements

- I'd like to thank my mentor Nisam Kumar for his help and advice throughout this project. His encouragement and feedback we're invaluable in the completion of this project.
- I would also like to thank Jim Morel, Tim Nelson, Stefan and Simen Daehlin from the code-institute for all their help and advice during our tutor sessions and masterclasses.

