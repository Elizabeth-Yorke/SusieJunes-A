# Testing

Resturn back to the [README.md] (README.md) file.

## Validating Code

### HTML

The following validation has been done using the recommended [HTML W3C Validator](https://validator.w3.org) using the live, deployed site using the site links shown below.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C] (https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2F)| ![screenshot](assets/documentation/validation/validation-screenshot-index.html.png) | No errors: Initial errors found and fixed.|
| Menu | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Fmenu.html) | ![screenshot](assets/documentation/validation/validation-screenshot-menu.html.png) | No errors: Initial errors found and fixed.|
| Catering | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Fcatering.html) | ![screenshot](assets/documentation/validation/validation-screenshot-catering.html.png) | No errors: Initial errors found and fixed.|
| Reservations | [W3C](https://elizabeth-yorke.github.io/SusieJunes-A/reservations.html) | ![screenshot](assets/documentation/validation/validation-screenshot-reservations.html.png) | No errors: Initial errors found and fixed.|
| Reservations 2 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Freservations-2.html%3Fcustomer-name%3De%26customer-phone%3D00000000000%26customer-email%3D) | ![screenshot](assets/documentation/validation/validation-screenshot-reservations-2.html.png) | No errors: Initial errors found and fixed.|
| Reservations 3 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Freservations-3.html%3Freservation-date%3D2023-12-21%26reservation-time%3D12%253A30%26number-of-people%3D3) | ![screenshot](assets/documentation/validation/validation-screenshot-reservation-3.html.png) | No errors: Initial errors found and fixed.|
| Reservations 4 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Freservations-4.html%3Fadditional-info%3D) | ![screenshot](assets/documentation/validation/validation-screenshot-reservation-4.html.png) | No errors: Initial errors found and fixed.|

### CSS

The following validation has been done using the recommended [The W3C CSS Validaton Service](https://jigsaw.w3.org/css-validator/validator) using the live, deployed site using the site links shown below.

| Page | W3C URL | Screenshot | Notes |
| style.css| [W3C] (https://jigsaw.w3.org/css-validator/validator) | ![screenshot](assets/documentation/validation-screenshot-style.css.png) | No errors: Initial errors found and fixed.|

## Testing Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](assets/documentation/browser-testing/browser-testing-screenshot-chrome.jpeg.png) | Works as expected |
| Firefox | ![screenshot](assets/documentation/browser-testing/browser-testing-screenshot-mozilla.png) | Works as expected |
| Edge | ![screenshot](assets/documentation/browser-testing/browser-testing-screenshot-edge.jpeg) | Minor scaling issues |
| Brave | ![screenshot](assets/documentation/browser-testing/browser-testing-screenshot-brave.png) | Works as expected |
| Opera | ![screenshot](assets/documentation/browser-testing/browser-testing-screenshot-opera.png) | Works as expected|
| Avast | ![screenshot](assets/documentation/browser-testing/browser-testing-screenshot-avast.png) | Works as expected|

## Testing Different Screen Sizes

I used media genesis responsive design checker [Media Genesis responsive design checker] (https://www.responsivedesignchecker.com/checker.php?url=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2F&width=1400&height=700) to check how responsive Susie June's website is. I used the live, deployed site. Links below.

|Device|Screensize|URL|Screenshot|Notes|
| --- | --- | --- | --- | --- |
|Desktop 24"|Screensize 1920x1200|[screenshot](assets/documentation/responsivity/desktop1920x1200.png) |Works as expected|
|Desktop 20"|Screensize 1600x900|[screenshot](assets/documentation/responsivity/desktop1600x900.png) |Works as expected|
|Notebook 13"|Screensize 1024x800|[screenshot](assets/documentation/responsivity/notebook1024x800.png) |Works as expected|
|Tablet Apple iPad Pro|Screensize 1366x1024|[screenshot](assets/documentation/responsivity/tablet1366x1024.png) |Works as expected|
|Tablet Amazon Fire|Screensize 768x1024|[screenshot](assets/documentation/responsivity/tablet768x1024.png) |Works as expected|
|Tablet Nexus 7|Screensize 600x960|[screenshot](assets/documentation/responsivity/tablet600x900.png) |Works as expected|
|Phone Apple iPhone 7 Plus|Screensize 414x736|[screenshot](assets/documentation/responsivity/phone414x736.png) |Works as expected|
|Phone Google Pixel|Screensize 411x731|[screenshot](assets/documentation/responsivity/phone411x731.png) |Works as expected|
|Phone Sony Xperia Z3|Screensize 360x640|[screenshot](assets/documentation/responsivity/phone360x640.png) |Works as expected|

This section has been re-done since the initial responsivity checks, because I had to edit the image sizes and add some responsive coding 'd-none d-md-block col-lg-3' to the catering page, as some images were overlapping the text on one of the tablet screen sizes.

I also added this line of code 'height: calc(100vh -358px);' to style.css in order to make sure reservations 4, which is quite a short page, reaches the bottom of every screen size. This idea came from my mentor, Sheryl Goldberg.


## Testing Website Speed

I tested my deployed project using using PageSpeed Insights via web.dev [PageSpeed](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/kv7di1miqk?form_factor=mobile)

|Page|Screensize|PageSpeed URL|Screenshot|Notes|
| --- | --- | --- | --- | --- |
|Home|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/nhb0i6m80t?form_factor=mobile)|[screenshot](assets/documentation/pagespeed/index-phone.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap, Fontawesome and GoogleMaps.|
|Home|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/nhb0i6m80t?form_factor=desktop)|[screenshot](assets/documentation/pagespeed/index-desktop.png)| Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap, Fontawesome and GoogleMaps.|
|Menu|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/nhb0i6m80t?form_factor=mobile)|[screenshot](assets/documentation/pagespeed/menu-phone.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap and Fontawesome.|
|Menu|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/nhb0i6m80t?form_factor=desktop)|[screenshot](assets/documentation/pagespeed/menu-desktop.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap and Fontawesome.|
|Catering|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-catering-html/fhqxoa5fcg?form_factor=mobile)|[screenshot](assets/documentation/pagespeed/catering-phone.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap, Fontawesome and GoogleMaps.|
|Catering|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-catering-html/fhqxoa5fcg?form_factor=desktop)|[screenshot](assets/documentation/pagespeed/catering-desktop.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap, Fontawesome and GoogleMaps.|
|Reservations|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-reservations-html/t2scl1axgs?form_factor=mobile)|[screenshot](assets/documentation/pagespeed/reservations-phone.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap and Fontawesome.|
|Reservations|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-reservations-html/t2scl1axgs?form_factor=desktop)|[screenshot](assets/documentation/pagespeed/reservations-desktop.png)|Performs as expected. According to PageSpeed, the biggest performance problems are the links to Bootstrap and Fontawesome.|

## Fullfilling User Story Requirements

| User |User Story|Answer|Screenshot|
| --- | --- | --- | --- |
| New site user | I would like to know where this cafe is. |The 'Contact Us' section on the home page and the catering page includes the address and a map.| [screenshot](assets/documentation/user-stories/user-story-screenshot-contact-us.png)|
| New site user | I would like to know what kind of food is served here. | There is a menu page and a downloadable menu in the footer.| [screenshot](assets/documentation/user-stories/user-story-screenshot-menu.png) |
|New site user | I would like to see some reviews or quotes about this place. | There are some customer quotes in the 'Quotes' section on the home page, and on the catering page.| [screenshot](assets/documentation/user-story-screenshot-quotes-a.png)[screenshot](assets/documentation/user-stories/user-story-screenshot-quotes-b.png)|
|New and returning site user|I would like to know when the cafe is open.| This information is on the home page in the 'Opening Times' section.|[screenshot](assets/documentation/user-stories/user-story-screenshot-opening-times.png)|
|New and returning site user|I would like to know if I can bring my dog.| This information is in the 'About Us' section on the home page.|[screenshot](assets/documentation/user-stories/user-story-screenshot-about-us.png)|
|New and returning site user|I would like to be able to reserve a table.| There is an entire reservations page.|[screenshot](assets/documentation/user-stories/user-story-screenshot-reservations.png)|
|Returning site user| I love the food and would like to know if they do functions. | This information is on the 'Catering' page. | [screenshot](assets/documentation/user-stories/validation-screenshot-catering.html.png) |
|Returning site user| I would like to be able to reassure my friend that her wheelchair will get to the tables in this cafe.| This information is in the 'About Us' section on the home page. | [screenshot](assets/documentation/user-stories/user-story-screenshot-about-us.png) |
|Returning site user| I would like to follow this cafe on social media so I can see if they are doing any promotions I'm interested in. | There is a link to the cafe facebook page in the 'footer' section on the home page. | [screenshot](assets/documentation/user-stories/user-story-screenshot-social.png) |
| Owners | We want our branding showing really strongly. | Every page of the website shows the cafe logo, name, slogan, photo and brand colours. | [screenshot](assets/documentation/user-stories/user-story-screenshot-header.png) |
| Owners | We want photos of our food on the website. | There are photos of their food all over the menu page and the catering page. Unfortunately I am still waiting for the owners to provide me with a picture of a hot sandwich and an omelette, as those two pictures are currently still pexels pictures waiting to be replaced. | [screenshot](assets/documentation/user-stories/user-story-screenshot-menu.png) |
| Owners | We want honest reviews from our customers on there. | The quotes on the website are genuine customer quotes, but the pictures of the customers are all from pexels. The plan is that this will change when they interview some customers who don't mind their photos being taken. | [screenshot](assets/documentation/user-stories/user-story-screenshot-quotes-a.png) |

## Debugging

I encountered a few bugs, particularly in during the testing phase. Here is what I did with each of them:

| Bug | Solution |
| --- | --- |
| I spent a long time trying to get the cafe logo into the menu bar with the link to the home page in tact. | I began by using col-11 for the menu bar and col-1 for the logo, but after trying many things, I eventually found a place within the bootstrapped menu bar where I could insert the logo.|
| My image filepaths worked perfectly in the IED, but when I deployed my project from github, some of them didn't work. | I went back and checked all the filepaths to make sure they were relative links rather than absolute paths. |
| W3C did not like the length of my comment lines on any of the pages. | I went back and shortened all my comment lines. |
| I realised that some of the code I had written was surplus to requirement. | I went back and removed excess code that wasn't doing anything. Most of these were alt attributes that I had added to things like <a> and <iframe> attributes. |
| W3C did not like the / in the end of my self closing attributes. | I went back and removed the closing / from the end of every self closing attribute.  |
| I realised some of the sematic elements I had used were surplus to requirement. In particular, W3C picked up on every section that was lacking a header, or had the header written in a table.| I went back and removed excess semantic elements. |
| I had forgotten to add alt tags to some images. | I went back and made sure every image had an alt tag. |
| Images on the catering page were overlapping on the sideways phone screen size | I changed d-sm-block to d-md-block for the quotes images and reduced the size of the larger images slightly. |


## Unfixed Bugs

| Bug | Comments |
| --- | --- |
| On every page, PageSpeed stated that 'render blocking resources' in the links to external websites were the things that were slowing the website down most. Bootstrap, Fontawesome and Googlemaps are sited continually. | I am not yet condifent enough in these types of coding to want to mess with bootstrapped or embedded code and links to external sites that are currently working, so I have left these as they are. |
| I am aware that the images would upload quicker if they were all saved in .webp format. | Unfortunately to convert more than 3 images per day to .webp you have to subscribe to the service, so I only converted the largest three images each day. I will continue to replace them when I can, but they may not all be done before the project is submitted.|