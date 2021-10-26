# Yoga & More

Yoga & More is a website that aims to inspire people to come and enjoy yoga, pilates and meditation in Helsingborg, Sweden. The site is targeted towards people who want a small studio with a pleasant, calm and relaxing setting for their classes. Yoga & More will be useful for people to be able to find out what times different classes are, who leads the class, how to get in touch, and where the studio is located.

A link to the live website can be found [here](https://mariechessler.github.io/yoga-and-more/index.html), and a link to the repository [here](https://github.com/MarieCHessler/yoga-and-more).

![Yoga & More on different screen sizes](assets/images/ym-screens.webp)

<br>

## Design

*** 

<br>

![Yoga & More 5 color palette](assets/images/ym-5-color-palette.webp)

### Color Palette

* The site's primary colors are (from left to right) Dark Jungle Green, Independence, Taupe Grey, Old Lavender and Isabelline, as seen in the picture above. They were derived using the online tool [Coolors](https://coolors.co), to complement each other in a good way, and still making contrasts possible.
    * Dark Jungle Green is used for text and menu, for best contrast on white.
    * Independence is used for dark backgrounds.
    * Taupe Grey is used as hover color and for Classes icons.
    * Old Lavender is used for the logo.
    * Isabelline is used instead of white for text and headings on dark background <br><br>
* The colors are all soft, to mirror the feeling in the studio and the colors in the hero image.

<br>

### Typography

* Raleway is used for text and menu, since it it easy to read. Fallback font is sans-serif.
* Montez is used for logo and headings, since it fits well with the soft feeling of yoga, pilates and meditation. Fallback font is sans-serif.
* Both fonts are from Google Fonts, where they are considered to be a popular pairing.

<br>

### Layout

* The majority of the content is placed in sections on the landing page, rather than on separate pages. The reason is that not all content would fill a whole page, and thus result in a lot of white space, or a footer placed too high on the page.
* The image gallery has been placed on a separate page, called Our Classes, since it takes up a lot of space.
* For desktop layout the content has been divided into up to four columns, for tablet at least one column less, and for mobile at least two columns less, depending on content and page.

<br>

### Wireframes

* Wireframes were used to structure the page content for desktop, tablet and mobile screens. The structure differs between screen sizes, for the user to be able to see and access the content properly.

<br>

![Wireframes for desktop](assets/images/ym-wf-desktop.webp)
![Wireframes for tablet](assets/images/ym-wf-tablet.webp)
![Wireframes for mobile](assets/images/ym-wf-mobile.webp)

<br>

## Features

***

The features described below have been implemented to give the user a pleasant experience, with a site that contains useful information and imagery, and is easy to navigate.

<br>

### Existing features

* **Navigation bar**
    * The fully responsive navigation bar holds the logo and the menu.
    * The logo links back to the landing page, which is considered best practice. In this case it helps the user get back from the Our Classes page.
    * The full menu is featured on the landing page, where it links to the different sections in the page - Home, Classes, About Us and Contact. Since internal links cannot be used between pages only Home is featured on the Our Classes page, providing the user with a link back to the landing page.

![Navigation bar](assets/images/ym-navigation.webp)

<br>

* **Landing page (hero) image**
    * The top of the landing page includes a hero image, with an animation to catch the users attention.
    * The image also has text overlay that welcomes the user to the page, and indicates that the studio is taking care of both body and mind.

![Hero image with welcoming message](assets/images/ym-hero-welcome.webp)

<br>

* **Classes and Times section**
    * The Classes and Times section includes the classes and times for yoga, pilates, meditation and private classes, which makes it easy for the user to see what classes are the most suitable.
    * The short description of the different classes are helpful for the user to find out what there is to choose from and what level of experience is needed.
    * The fixed background image enhances feeling of the studio, thanks to the harmonious colors and content.
    * The button shaped link below the text invites the user to take a look at some pictures from the studio and get inspired.

![Classes and Times section](assets/images/ym-classes.webp)

<br>

* **About Us section**
    * The About Us section allows the user to see who is teaching the different classes, and get a bit of background information about the different teachers. 
    * Photos of the teachers help the user become familiar with their faces, and makes it easier to identify them when arriving at the studio. The photos also build trust, since the teachers look nice and kind.

![About Us section](assets/images/ym-about-us.webp)

<br>

* **Contact section**
    * The Contact section gives the user excellent opportunities to get in touch with Yoga & More, as it includes a contact form, a phone number and an address to the studio.
    * In the form it is mandatory for the user to provide first and last name, e-mail address and what he or she is contacting the studio about, so the staff knows who has contacted them and can choose who is best suited to answer the question. The message field can be used, but is optional.
    * The background image has a calming effect, due to the balancing stones and the water.
    * At the end of the section the user finds a Google Map, where the studio's location is marked, which makes it easier to find the place and plan the visit.

![Contact section](assets/images/ym-contact.webp)

* **Footer section**
    * In the footer the user finds copyright information and links to Yoga & More's social media channels on Instagram, Facebook, Twitter and YouTube. The links open in new tabs to make it easy for the user to navigate without using the back button.
    * The footer incourages the user to connect with Yoga & More on social media, which helps the him or her stay updated and feel included.
    * The section is included in all pages

![Footer section](assets/images/ym-footer.webp)

<br>

* **Our Classes page**
    * The Our Classes page shows pictures of teachers and classes in the studio, to give the user a feeling for the place.
    * This page is a great way for the user to get a feel for the place and a good view of what the different classes look like.
    * The logo and the Home menu item at the top provide the user with two easy ways to get back to the landing page.

![Our Classes pictures](assets/images/ym-our-classes.webp)

<br>

### Features for the future
* Back to top link, or hamburger menu, beside section headlines. Needed if content grows.
* Send functionality for the contact form. As of now GET is used instead of POST, since there is nowhere to post the info to. Validation is needed, and I have not learned that yet, so I have used GET together with an action that takes the user to a Thank you page that opens in a new window.
* A video where the teachers introduce the studio and themselves.

<br>

## Testing

***

The site has been tested through both validator testing and manual testing. Details are provided in the sections below.

<br>

### Validator testing
* HTML
    * No errors or warnings were found on index.html, our-classes.html or thank-you.html, when passing through the official [W3C validator](https://validator.w3.org/#validate_by_input).

<br>

* CSS
    * No errors were found on style.css, when passing through the official [W3C (Jigsaw) validator](https://jigsaw.w3.org/css-validator/#validate_by_input).
    * One warning was returned, saying "Imported style sheets are not checked in direct input and file upload modes".

<br>

### Manual testing
* The following has been checked manually, on different devices (see below):
    * Links, menu items and buttons working properly.
    * External links and Thank you page opening in new tabs.
    * Form working properly, asking user to fill out mandatory fields.
    * Images showing in right proportions and places.
    * Fixed image staying in the background on scroll.
    * Map showing the right adress, and opening in new tab when Show larger map is clicked.
    * Responsiveness working properly, and no content moving in unexpected ways when screen size changes.

<br>

* Checks have been made on these devices and in these browsers:
    * iMac 27"
    * MacBook Pro 13"
    * iPhone XR and 11
    * HP EliteBook
    * HP ProBook
    * Safari - Version 15.0 (16612.1.29.41.4, 16612)
    * Chrome - Version 95.0.4638.54 (Official version) (x86_64)
    * Edge - Version 95.0.1020.30 (Official version) (64 bit)

<br>

* The site's responsiveness has been checked in Google DevTools throughout the project.

<br>

* The site has been run in Lighthouse, with the following results for the landing page and the page Our Classes on desktop.

![Lighthouse result landing page desktop](assets/images/lighthouse-landing-desktop.webp)
![Lighthouse result Our Classes page desktop](assets/images/lighthouse-our-classes-desktop.webp)

<br>

* The site has been run in Lighthouse with the following results for the landing page and the page Our Classes on mobile.

![Lighthouse result landing page mobile](assets/images/lighthouse-landing-mobile.webp)
![Lighthouse result Our Classes page mobile](assets/images/lighthouse-our-classes-mobile.webp)

<br>

* The reasons the score is less than 100% on Performance are the following:
    * For the landing page on desktop, scoring 99%, I did not manage to solve how to use passive listeners, or serve static assets (images) with an efficient cache policy.
    * For the landing page on mobile, scoring 93%, Largest Contentful Paint had been improved, but still was not excellent. Also, I did not manage to solve how to use passive listeners, or serve static assets (images) with an efficient cache policy.
    * For the Our Classes page on mobile, scoring 98%, I did not manage to solve how to serve static assets (images) with an efficient cache policy.

<br>

## Bugs

Unfixed bugs</h3>
    <p>Mention unfixed bugs and why they are not fixed, shortcomings etc</p>

## Deployment

***

### GitHub Pages
The site was deployed to GitHub pages by following these steps:

<br>

* Log in to GitHub.
* Go to the GitHub repository.
* Click on Settings.
* Scroll down to the GitHub Pages section and click on "Check it out here!".
* Under Source, click the arrow and choose Branch: main.
* After a little while the page is automatically refreshed and you get a message on green background saying "Your site is published at: ...", with a link to your site, showing that your deployment was successful.

The live link can be found here: https://mariechessler.github.io/yoga-and-more/index.html

<h2>Credits</h2>
    <p>The references mentioned in this section have been used when it comes to content and media</p>

<h3>Content</h3>
    <ul>
        <li>Reference 1</li>
    </ul>

<h3>Media</h3>
    <ul>
        <li>Reference 1</li>
    </ul>