# Testing

Resturn back to the [README.md] (README.md) file.

## Validating Code

### HTML

The following validation has been done using the recommended [HTML W3C Validator](https://validator.w3.org) using the live, deployed site using the site links shown below.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C] (https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2F)| ![screenshot](assets/documentation/validation-screenshot-index.html.png) | No errors: Initial errors found and fixed.|
| Menu | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Fmenu.html) | ![screenshot](assets/documentation/validation-screenshot-menu.html.png) | No errors: Initial errors found and fixed.|
| Catering | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Fcatering.html) | ![screenshot](assets/documentation/validation-screenshot-catering.html.png) | No errors: Initial errors found and fixed.|
| Reservations | [W3C](https://elizabeth-yorke.github.io/SusieJunes-A/reservations.html) | ![screenshot](assets/documentation/validation-screenshot-reservations.html.png) | No errors: Initial errors found and fixed.|
| Reservations 2 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Freservations-2.html%3Fcustomer-name%3De%26customer-phone%3D00000000000%26customer-email%3D) | ![screenshot](assets/documentation/validation-screenshot-reservations-2.html.png) | No errors: Initial errors found and fixed.|
| Reservations 3 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Freservations-3.html%3Freservation-date%3D2023-12-21%26reservation-time%3D12%253A30%26number-of-people%3D3) | ![screenshot](assets/documentation/validation-screenshot-reservation-3.html.png) | No errors: Initial errors found and fixed.|
| Reservations 4 | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2Freservations-4.html%3Fadditional-info%3D) | ![screenshot](assets/documentation/validation-screenshot-reservation-4.html.png) | No errors: Initial errors found and fixed.|

### CSS

The following validation has been done using the recommended [The W3C CSS Validaton Service](https://jigsaw.w3.org/css-validator/validator) using the live, deployed site using the site links shown below.

| Page | W3C URL | Screenshot | Notes |
| style.css| [W3C] (https://jigsaw.w3.org/css-validator/validator) | ![screenshot](assets/documentation/validation-screenshot-style.css.png) | No errors: Initial errors found and fixed.|

## Testing Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](assets/documentation/browser-testing-screenshot-chrome.jpeg.png) | Works as expected |
| Firefox | ![screenshot](assets/documentation/browser-testing-screenshot-mozilla.png) | Works as expected |
| Edge | ![screenshot](assets/documentation/browser-testing-screenshot-edge.jpeg) | Minor scaling issues |
| Brave | ![screenshot](assets/documentation/browser-testing-screenshot-brave.png) | Works as expected |
| Opera | ![screenshot](assets/documentation/browser-testing-screenshot-opera.png) | Works as expected|
| Avast | ![screenshot](assets/documentation/browser-testing-screenshot-avast.png) | Works as expected|

## Testing Responsiveness

I used media genesis responsive design checker [Media Genesis responsive design checker] (https://www.responsivedesignchecker.com/checker.php?url=https%3A%2F%2Felizabeth-yorke.github.io%2FSusieJunes-A%2F&width=1400&height=700) to check how responsive Susie June's website is. I used the live, deployed site. Links below.

|Device|Screensize|URL|Screenshot|Notes|
| --- | --- | --- | --- | --- |
|Desktop 24"|Screensize 1920x1200|[screenshot](assets/documentation/media-genesis-screenshot-1920-1200.png) |Works as expected|
|Desktop 20"|Screensize 1600x900|[screenshot](assets/documentation/media-genesis-screenshot-1600x900.png) |Works as expected|
|Notebook 13"|Screensize 1024x800|[screenshot](assets/documentation/media-genesis-screenshot-1024x800.png) |Works as expected|
|Tablet Apple iPad Pro|Screensize 1366x1024|[screenshot](assets/documentation/media-genesis-screenshot-1366x1024.png) |Works as expected|
|Tablet Amazon Fire|Screensize 768x1024|[screenshot](assets/documentation/media-genesis-screenshot-768x1024.png) |Some image issues on the catering page only|
|Tablet Nexus 7|Screensize 600x960|[screenshot](assets/documentation/media-genesis-screenshot-600x960.png) |Works as expected|
|Phone Apple iPhone 7 Plus|Screensize 414x736|[screenshot](assets/documentation/media-genesis-screenshot-414x736.png) |Works as expected|
|Phone Google Pixel|Screensize 411x731|[screenshot](assets/documentation/media-genesis-screenshot-411x731.png) |Works as expected|
|Phone Sony Xperia Z3|Screensize 360x640|[screenshot](assets/documentation/media-genesis-screenshot-360x640.png) |Works as expected|


## Testing Website Speed

I tested my deployed project using using PageSpeed Insights via web.dev [PageSpeed](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/kv7di1miqk?form_factor=mobile)

|Page|Screensize|PageSpeed URL|Screenshot|Notes|
| --- | --- | --- | --- | --- |
|Home|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/kv7di1miqk?form_factor=mobile)|[screenshot](assets/documentation/pagespeed-screenshot-home-mobile.png)|The biggest performance problems are the bootstrap and fontawesome links. I can't improve the contrast of the writing on the company logo, but I have been back and edited the colour scheme as much as I can without losing the branding.|
|Home|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A/dyi2rohaa2?form_factor=desktop)|[screenshot](assets/documentation/pagespeed-screenshot-home-desktop.png)| Performs as expected. Missing unnecesary table headers and colour contrast in parts relating to the branding noted.|
|Menu|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-menu-html/76lh4lzdfc?form_factor=mobile)|[screenshot](assets/documentation/pagespeed-screenshot-menu-mobile.png)|Slower loading times due to larger images|
|Menu|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-menu-html/76lh4lzdfc?form_factor=desktop)|[screenshot](assets/documentation/pagespeed-screenshot-menu-desktop.png)|Slower loading times due to larger images|
|Catering|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-catering-html/zhs86d2g1h?form_factor=mobile)|[screenshot](assets/documentation/pagespeed-screenshot-catering-mobile.png)|Large images making loading slower. Table headers missing intentionally and colour contrast issues due to branding.|
|Catering|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-catering-html/zhs86d2g1h?form_factor=desktop)|[screenshot](assets/documentation/pagespeed-screenshot-catering-desktop.png)|Large images making loading slower. Table headers missing and colour contrast issues due to branding.|
|Reservations|Mobile|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-reservations-html/urehulurj0?form_factor=mobile)|[screenshot](assets/documentation/pagespeed-screenshot-reservations-mobile.png)|Biggest issues here due to boostrap and fontawesome links.|
|Reservations|Desktop|[PageSpeed URL](https://pagespeed.web.dev/analysis/https-elizabeth-yorke-github-io-SusieJunes-A-reservations-html/urehulurj0?form_factor=desktop)|[screenshot](assets/documentation/pagespeed-screenshot-reservations-desktop.png)|Everything over 90 here. Branding colour contrast is an issue again.|

## Fullfilling User Story Requirements

| User |User Story|Answer|Screenshot|
| --- | --- | --- | --- |
| New site user | I would like to know where this cafe is. |The 'Contact Us' section on the home page and the catering page includes the address and a map.| [screenshot](assets/documentation/user-story-screenshot-contact-us.png)|
| New site user | I would like to know what kind of food is served here. | There is a menu page and a downloadable menu in the footer.| [screenshot](assets/documentation/user-story-screenshot-menu.png) |
|New site user | I would like to see some reviews or quotes about this place. | There are some customer quotes in the 'Quotes' section on the home page, and on the catering page.| [screenshot](assets/documentation/user-story-screenshot-quotes-a.png)[screenshot](assets/documentation/user-story-screenshot-quotes-b.png)|
|New and returning site user|I would like to know when the cafe is open.| This information is on the home page in the 'Opening Times' section.|[screenshot](assets/documentation/user-story-screenshot-opening-times.png)|
|New and returning site user|I would like to know if I can bring my dog.| This information is in the 'About Us' section on the home page.|[screenshot](assets/documentation/user-story-screenshot-about-us.png)|
|New and returning site user|I would like to be able to reserve a table.| There is an entire reservations page.|[screenshot](assets/documentation/user-story-screenshot-reservations.png)|
|Returning site user| I love the food and would like to know if they do functions. | This information is on the 'Catering' page. | [screenshot](assets/documentation/validation-screenshot-catering.html.png) |
|Returning site user| I would like to be able to reassure my friend that her wheelchair will get to the tables in this cafe.| This information is in the 'About Us' section on the home page. | [screenshot](assets/documentation/user-story-screenshot-about-us.png) |
|Returning site user| I would like to follow this cafe on social media so I can see if they are doing any promotions I'm interested in. | There is a link to the cafe facebook page in the 'footer' section on the home page. | [screenshot](assets/documentation/user-story-screenshot-social.png) |
| Owners | We want our branding showing really strongly. | Every page of the website shows the cafe logo, name, slogan, photo and brand colours. | [screenshot](assets/documentation/user-story-screenshot-header.png) |
| Owners | We want photos of our food on the website. | There are photos of their food all over the menu page and the catering page. Unfortunately I am still waiting for the owners to provide me with a picture of a hot sandwich and an omelette, as those two pictures are currently still pexels pictures waiting to be replaced. | [screenshot](assets/documentation/user-story-screenshot-menu.png) |
| Owners | We want honest reviews from our customers on there. | The quotes on the website are genuine customer quotes, but the pictures of the customers are all from pexels. The plan is that this will change when they interview some customers who don't mind their photos being taken. | [screenshot](assets/documentation/user-story-screenshot-quotes-a.png) |

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

| Bug | Solution |
| --- | --- |
| PageSpeed was concerned about the colour contrast in every section of the website using color-scheme-b. This is a major problem because color-scheme-b was taken directly from the actual cafe branding. My client said that I can't produce a website with for this cafe without at least having the cafe name written in the same colours as it is on the actual cafe frontage and the actual cafe logo in some places on the website. | At first, I tried changing #F2F2F2 to #FFFFFF, because the owners were happy with that slight change, and I was hoping it might be enough to satisfy PageSpeed. It wasn't. I then reconfigured the colouring of every page to make sure I wasn't using color-scheme-b where there was writing on a background other than in the title strip and the footer. This was a particularly laborious task on the menu page because it is a long page, and I had broken in into small chunks using different variations of the branding colours to make it more palatable to the reader. I also took care to use as much of the color-scheme-b background colour as I could in sections where there was no writing, to make sure I didn't lose the branding colours. I looked at adding outlines to the text on the name strip and footer, to improve the colour contrast, but I couldn't find a workable way to do this. I did manage to add shadows to the text, which do improve the visual contrast without losing the branding colours, but they don't have much impact on PageSpeed's interpretation of the colour contrast.|  
| PageSpeed thinks that the Fontawesome links, and most of my Bootstrapping is slowing down the website. | I am not yet condifent enough in these types of coding to want to mess with bootsrapped elements that are currently working, so I have left these as they are. |