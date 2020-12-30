# Cartel Coffee Website - Testing

[Link to README.md file](README.md)

[Link to Deployed site](https://nickassafkirk.github.io/Cartel-Coffee/index.html)


## Manual Testing
---
Manual testing involved going through the site thoroughly to ensure that the format, layout, styles and functionality of the site perform as intended. 
Testing involved: 
1. Testing the site using multiple browsers to ensure cross-browser compatibility.
   The following browsers were tested for the current deployed version of this site:

   | Browser       | Compatible |
   | --------------|------------|
   | Chrome        |   &#9745;  |
   | Safari        |   &#9745;  |
   | Firefox       |   &#9745;  |
   | Opera         |   &#9745;  |
   | Microsoft Edge|   &#9745;  |

2. Testing the site across a range of devices to ensure a responsive site that provides a great user experience on all devices.
   The site was tested on: 

   | IOS           | Windows/Android |
   |---------------|-----------------|
   |Macbook Pro 13"| Hp Pavillion 22"|
   |Iphone 5s      | Samsung a51     |
   |Iphone 6s Plus |
   |Iphone SE      |
   |Iphone XS      |
   |Ipad Mini      |
   

---
  
## Common Elements:

### 1: Navbar 
* **Aim:** Navbar is expected to be located fullwidth at the top of all pages. Navbar logo and links should scale to fit larger/smaller screenwidth and 
avoid overflow. Navbar should expand/collapse at set breakpoint.    
* **Test:** Window was expanded and collapsed to ensure navbar occupies full screenwidth on all screenwidths and ensured that navbar expands and collapses at the correct breakpoints. Ensured that fonts scale to avoid overflow on different screensizes. 
navbar functions as intended.   
* **Result:** Navbar functions as intended across all screensizes. 

 ### Navbar Logo:
 * **Aim:** When clicking the brand logo I expect to be taken to the homepage (index.html).   
 * **Test:** To test this I clicked the logo on each site page and observed that it linked back to the homepage on each page. 
 * **Result:** The Logo links to the site homepage on all pages 

 ### Navbar links: 
 * **Aim:** I expect each link to take the user to the correct page as indicated by the link name. Ie "Menu links to "menu.html", "Shop" links to "shop.html" etc...  
 * **Test:** I verified that the navbar links link to the correct page on all site pages and that the correct active class is displayed for each page.     
 * **Result:** I verified that the navbar links work as intended for all pages 

### Navbar Links Hover:
 * **Aim:** Navbar links are highlighted on hover to encourage user click activity.    
 * **Test:** Hovered mouse over navbar links.                 
 * **Result:** Verified that navbar link hover functionality works as intended.

### Navbar Item Active class: 
 * **Aim:** The navbar item for the Active page should be highlighted and made bold to indicate a user's current page location  
 * **Test:** Visit each site page and ensure correct tab is higlighted when on it's corresponding page.   
 * **Result:** Active class is working as intended 
 * **Note:** As the menu "Book" Link, links to a specific section ID on the "contact.html" page. The design decision
 was made to highlight the "Contact" nav-item and not the "Book" nav-item when book is selected. this was to reinforce that the "Book" section is housed with in the "contact.html" page.  

### Navbar expand/Collapse
 * **Aim:** On smaller devices navbar links collapse into the burger stack icon. Expected behavior is that a dropdown menu will open and close by clicking burger stack icon.       
 * **Test:** Clicked the burger stack icon on all pages and touch and cursor devices. Expanded and minimized the viewport to test the collapse functionality.       
 * **Result:** Verified that burger stack functions as anticipated on click, that the navbar expands/collapses at the correct breakpoint and that navbar items are aligned to right as desired.     
 
## Footer

* **Aim:** Footer should occupy 100% screenwidth across all screensizes and be present at the bottom of the page at all times.
 The footer columns should re-shuffle at 768px breakpoint to ensure proper display on smaller screenwidths. 
* **Test:** Checked footer presence on all pages. Checked that footer re-order collumns at the correct breakpoint by expanding/minimizing viewport and testing on tablet and mobile devices.  
* **Result:** Footer is present on all pages and scales correctly for good responsive design. 

 ### Footer links
 * **Aim:** Footer links are expected to link to their relevant page or page section.
 * **Test:** To verify this I tested every footer link on each site page by clicking each link to ensure that footer links were linking to the desired page. 
 * **Result:** Footer links work as intended on all pages.

 ### Social media links
 * **Aim:** The social media links are intended to link the instagram, facebook and twitters homepages respectively. 
 * **Test:** To test this I visited each page and clicked each social media icon and observed the result. I verified that all footer social media links link to the correct website across all site pages and open a new tab to allow easy navigation back to site.     
 * **Result:** Social media links work as intended.

 ### Links/Buttons:
 * **Aim:** All links andd buttons should link to the correct page or section labelled in the link or buttons. Links that point to external sites and resources. links and buttons should
 utilise consistent color motifs to encourage first time learning of navigation elements. 
 should have target set to _blank to ensure a new tab is opened to ensure easy navigation back to site is possible. 
 * **Test:** To test this I tested all links to ensure links point to correct urls and target attributes are set correctly. 
 * **Result:** All links and buttons render correctly and point to the correct destination.

### Covid-19 Alert
* **Aim:** The Covid-19 alert banner should appear upon opening at the top of each page. The alert should take up the full screen-width.
The alert should exclude some of it's accompanying text on small screen-widths. The Alert should have a working link to a [mock terms and conditions page](about.html).
Users should be able to close the alert using it's "close icon".    
* **Test:** To test this I visited each site page and observed that the alert was present and occupies the full screen-width of each page. 
I tested on mobile, tablet and using a responsive browser window to ensure that the alert displays a shortened message at the correct-breakpoint. 
I tested the link for both alert types on each page and confirmed that the links are working as intended. I tested that the alert can be closed using the accompanying icon.        
* **Result:** The alerts are displaying as intended, have working links and can be closed by the user if desired. 

---

## index.html

### Image Carousel: 
* **Aim:** The Image carousel should appear directly below the navbar at the top of the index.html page. The carousel should span the full screenwidth. The carousel should display centered
carousel captions to provide context for the sites purpose. The carousel should have three image slides. The carousel should automatically scroll between slides. The carousel should have visible controls to allow manual scrolling. 
The carousel should display alternate image aspect ratios for large and small screen widths.  
* **Test:** To test I visited the homepage on all browsers, mobile and tablet devices and observed the carousel. I used a responsive browser window to test that the banner changes image at the correct breakpoint. I tested the slide control buttons to ensure they function correctly. 
I observed the captions to ensure their position remains centered on the slide and scales to fit each slide image. 
* **Result:** I confirmed that the carousel is has desired styles and behaviour, is positioned correctly, scales to fit multiple viewport sizes and has working slide control buttons. 

 ### Welcome section: 
 **Aim:** On desktop it is intended that the full welcome paragraph is revealed. On mobile the paragraph becomes a + icon which reveals a collapsed paragraph on click. 
 **Test:** To test this I verified the + icon and collapse paragraph are not displayed on screenwidths greater than 576px. I also verified that the welcome text is 
 displayed as intended across browsers. To test mobile functinality I ensured that clicking the + icon expands and collapses the welcome paragraph card. I tested that the + icon is higlighted on hover 
 to hint interactivity.
 **Result:** The welcome section is styled and functioning as intended.  

 ### Menu category tile section:
 **Aim:** Menu image tiles should be clickable links to a corresponding menu.html section. Image tiles should display responsive design to reorder at the correct breakpoint. Alternative images with landscape or portrait aspect-ratio should be displayed 
 at the correct breakpoint. The tile's overlaying text should not overflow it's container. Upon hover each tile should be highlighted and it's overlaying text should be hidden to incourage click behaviour.   
 **Test:** To test that the Menu category tiles were operating as intended I viewed this section on multiple devices and with a responsive browser window and ensured there was no overflow or alignment issues on any screenwidths. 
 I also tested that the image tiles are working and each link directs to the correct section IDs on the menu page. I tested hover functionality by hovering the cursor over each tile and ensured that the hover behaviour functions as intended across browsers.   
 **Result:** The homepage menu category tiles function and format as intended.

### Shop popular category tile section:
* **Aim:** The entire shop image tiles should be clickable links to a corresponding shop.html section. Image tiles should display responsive design to reorder at the correct breakpoint. Overlaying text and imitation-button should scale correctly on all screenwidths. 
Tiles be highlighted upon hover and the imitation button should change it's background color on hover to encourage click behaviour.     
* **Test:** To test that the shop category tiles were operating as intended I viewed this section on multiple devices and with a responsive browser window and ensured there was no overflow or alignment issues on any screenwidths. 
 I also tested that the image tiles are working and each link directs to the correct section IDs on the shop page. I tested hover functionality by hovering the cursor over each tile and ensured that the hover behaviour functions as intended across browsers. 
 I used a responsive browser window to confirm that the tiles re-align at the correct breakpoint.   
* **Result:** Shop category tiles display and function as intended.

## menu.html

### Body
* **Aim:** A large background image will occupy the body of the menu.html with no whitespace between the
navbar and footer. The background image should be relevant to the page content to reinforce the page subject to new users. The background image should contrast the section containers for appealing visual impact and improved readability. 
* **Test:** To test I viewed the menu.html page and confirmed that the background image occupies the full background between the navbar and footer on all devices and window sizes. I confirmed that the background image shows a relevant image subject and
helps to provide page context to first time users. I confrimed that the background image provides adequate contrast to section containers and is coherent with the color palette choen for this page. 
* **Result:** The body background functions as intended.

### Intro Section
* **Aim:**
* **Test:**
* **Result:**

### Sub navigation Menu
* **Aim:**
* **Test:**
* **Result:**

### Food Menu
* **Aim:**
* **Test:**
* **Result:**

### Dessert Menu
* **Aim:**
* **Test:**
* **Result:**

### Call Menu
* **Aim:**
* **Test:**
* **Result:**



## shop.html

### Shop Modal
* **Aim:** Shop modal should appear upon loading of shop.html page. Modal should scroll to center on page if a section ID is referenced from footer links.
 The modal should close by clicking on (X) icon or by clicking outside of the modal box.    
* **Test:** To test I opened the shop.html page and confirmed that the modal opens upon loading of the shop page. I confirmed that the modal opens top of center on the page.
 I tested that the modal scrolls to center on page by clicking the shop section links via the footer navigation. 
 I tested that the modal closes by cicking the close (X) Icon or by clicking outside of the modal box.  
* **Result:** The Modal is operating as intended.    
* **Note:** For future updates of this project, it is my intention to use cookies to ensure that this modal is only opened the first time a user
 visits the shop.html page in a session. This modal will be completely removed when online checkout functionality is added to the site. 

### Intro Jumbotron
* **Aim:** The intro Jumbotron should be the first section displayed below the navbar on the shop.html page. The jumbotron should be centered and should only span 60% of the viewport width on XL screen sizes. 
* **Test:** To test I viewed the shop.html page and observed that the intro jumbotron displays as intended. Using a responsive browser window, mobile and tablet views I confirmed that the jumbotron works as inteded. 
* **Result:** The shop intro jumbotron works as intended

### Products Sections
* **Aim:** Product tiles should center on page. Product tiles should have working images. Product tiles should have inactive buttons. Product tiles should behave responsively and reorder at the correct
breakpoint. The "see more products icons" should be revealed to fill blank space upon re-ordering of tiles at the correct breakpoint. The "see more products icons" should link the next page section.   
* **Test:** To test I viewed the shop page on multiple devices and viewport sizes. I confirmed that the alignment and format of products tiles was displaying correctly.  
I confirmed that product tiles were of equal height and width and shared space evenly. By viewing the page on an XL screen I confirmed that the page content is limited to 60% viewport width on XL screens.    
By viewing the shop page on a responsive browser window, tablet and mobile devices I confirmed that the product tiles behave responsively and re-order at the correct breakpoint.
I also confirmed that the "see more products sections" appear at the correct breakpoint and each icon navigates correctly to the next category of products.     
* **Result:** Product tiles on the shop page function as intended.

### Section Headings
* **Aim:** Section headings should span the same screen width as the product tiles and jumbotrons. 
* **Test:** To test I viewed the shop page on multiple devices and viewport sizes. I confirmed that the alignment and format of the section headings were displaying correctly.   
By viewing the page on an XL screen I confirmed that the page content is limited to 60% viewport width on XL screens.   
By viewing the shop page on a responsive browser window, tablet and mobile devices I confirmed that the section headings behave responsively to occupy the same screenwidth as the product tiles and jumbotrons.    
* **Result:** Shop page section headings display as intended.

### Merchandise Jumbotron
* **Aim:** The merchandise Jumbotron should be the last section displayed above the footer on the shop.html page. The jumbotron should be centered and should only span 60% of the viewport width on XL screen sizes. 
* **Test:** To test I viewed the shop.html page and observed that the merchandise jumbotron displays as intended. Using a responsive browser window, mobile and tablet views I confirmed that the jumbotron works as intended. 
* **Result:** The shop merchandise jumbotron works as intended.


## Contact.html

Forms:
 Inputs should provide validation hints if required fields are not filled out. If validation does not occur, form submission should be prohibitted. 
 Upon successful submission page should reload to a submission success page to notify the user of successful form submission. 
 To test: went through all forms and ensured submission is not possible without validation. 
 Checked that validation messages occur if requered fields are left empty. 
 confirmed that page reloads to success page upon succesfful validation and submission.
 Outcome: Forms operate as intended. 

## about.html

## submit.html

### Covid-19 Alert
* **Aim:**
* **Test:**
* **Result:**


 Bugs
footer: brew equipment not linking correctly

homepage: dessert tile not linking correctly

image alts for all images

Menu page background image is too grey on mobile. It looks like the page hasn't loaded correctly. 

--- 

## User stories testing: 

---

## Additional Testing

---

## Bugs

### Fixed

* Bug: Navbar toggle burger stack stacking vertically on XS screensizes. 
  Fix: Added media query to navbar-brand so font-size shrinks on XS devices this left ample room for the burger stack icon and prevents vertical stacking of header items on XS devices.

* Bug: Undesired Indent in top right of Navbar and footer.
  Fix: Used view port width value of 100 to ensure that the navbar occupies the full width of the screen across all screen sizes. Media queries are utilised to adjust the font-size of the logo and navbar items on different screenwidths
  to ensure that content overflow did not create a similar issue.

* Bug: Carousel images not scaling correctly when changing screensizes. 
  Fix: A main image with a portrait aspect-ratio is used on smaller screensizes which primarily utilise viewports more suited to portrait style images. An Alternative image with a landscape aspect-ratio has been added for larger screen-widths. I decided this was a better tactic than using the object-fit property because it ensures
  Images are not cropped on responsive viewports.

* Bug: Labels for tiles not scaling correctly when changing screensizes. On smaller screensizes the label headings were moving off their desired position in the center of the image tiles.
  Fix: I used position: relative and top and bottom percentage values to fix the headings to the image tiles regardless of screensize. media queries are used to edit the font-size to ensure, overflow does not cause 
  undesireable rendering on smaller viewports and devices.

* **Bug:** Category headings overflow housing containers on tablet due to excessive font-size at the 768px breakpoint. 
  ![cathead overflow bug](assets/images/bugs/h5_cathead_overflow_bug.png)
  **fix:** Add additional media query for max-width: 1000px was used to control the font-size of the home page shop category tiles
  and ensure proportional heading size between the large and medium breakpoints. 

* **Bug:** Button placement on shop category homepage tiles not scaling correctly on mobile on IOS.
  **Fix:** Use position absolute and top positon 50% to position button relative to containing parent

* **Bug:** Footer `<li>` items were indented from the left and were overflowing their housing containers. 
  **Fix:** I removed the default left padding on unordered lists to ensure desired content spacing for footer list items. 

* **Bug:** Reoccuring undesireable indent to the right of body content causing alignment issues and content overflow. 
  **Fix:** I Removed the default right margin on the bootstrap container-fluid class that was causing alignment issues across site.

* **Bug:** Modal on Shop page was fixed to the top of the page. When using the footer navigation links to navigate to popular shop categories (coffee, subscriptions, equipment and merchandise), the user would be scrolled down the page.
  This meant that the modal was out of the viewport and customers could not interact with the shop page. 
  **Fix:** Using position: fixed, percentage top and left values and a transform value, I was able to ensure that the modal is position in the center of the screen even when the screen is scrolled. 
  The code used for this fix was taken from a CSS tricks article credited in the credits section of the accompanying [README.md](README.md) file

---

### Remaining Bugs To Be Fixed


### Other
**Overflow occuring when semantic html elements are used instead of divs:**
I attempted to use `<section>` elements instead of `<div>` elements on many of the page sections for better accessibility and best-practise. However in doing so I experience many undesireable bugs caused by content overflowing it's housing containers. 
On doing some research it would appear this is due to conflict between bootstrap and the use of semantic html elements. It would seem that some of bootstrap
styling specifically references `<div>` elements and thus replacing these elements with semantic elements results in unpredictable styling. Unfortunately it was not within the scope of this project 
to go through and create specific rules to allow the use of semantic html elements for some sections. 
