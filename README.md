# PP1 HTML/CSS: Wikström Photography

![smartmockups_lo3qd3ah](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/432bc965-b2b3-4eaa-9aae-5b67b72e51d6)
[Wikström Photography](https://humanslaughter.github.io/portfolio-project-1/)

This website is a portfolio of my own photographs that I've taken with my Nikon, Canon and S22 Ultra, with a purpose to be able to showcase my art to other's who also has an interest in photography in some way.
I've wanted to make a website for myself for a long time to be able to display my photographs and maybe even get more attraction from people who's looking for a photographer, and thought this would be a good idea as my Portfolio Project in HTML/CSS.

---

## Contents

* [Features](#features)
  * [Navigation Bar](#navigation-bar)
  * [Image On Home & Contact Page](#image-on-home--contact-page)
  * [Facebook Page Feed On Home Page](#facebook-page-feed-on-home-page)
  * [Footer](#footer)
  * [Gallery](#gallery)
  * [Contact Page](#contact-page)

* [Design](#design)
  * [Color Scheme](#color-scheme)
  * [Typography](#typography)

* [Testing](#testing)
  * [Validator Testing](#validator-testing)
  * [Known Bugs](#known-bugs)

* [Deployment & Local Development](#deployment--local-development)
 	* [Local Development](#local-development)
  		* [How To Fork](#how-to-fork)
  		* [How To Clone](#how-to-clone)

* [Credits](#credits)
  * [Content](#content)
  * [Media](#media)

---

## Features

### Navigation Bar
- Featured on all pages, full responsive, includes links to Logo, Home page, Gallery and Contact page, looks the same on each page for easy navigation.
- Allows users to easily navigate from each page on all devices without having to use the "back" button to go back to any previous page.

![Nav Bar](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/89b4004c-55a5-4a47-9d8d-cc35b69f7036)

### Image On Home & Contact Page
- Includes a logotype that I've made myself that is also used on my Facebook page, Twitter and Instagram, to make it easy to reconize my "brand".
- Has a text underneath that lets you know that it's about photography.

![Landing Page Image + Text](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/5d36c0b5-f200-4f4b-94a1-ec3360d43823)

### Facebook Page Feed On Home Page
- Allows users to see a sample of my photographs that exists on my Facebook page. When a photo is clicked, a new tab opens up to that specific post on Facebook. It will automatically include any new photo that is posted.

![Facebook Feed](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/59d3caaf-bbab-46a0-a379-45a2fc22d231)

### Footer
- Includes icons with links to my social media accounts on Facebook, Twitter and Instagram. Opens in a new tab for easy navigation.

![Footer](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/6fb76320-9385-4856-8fa6-cc7cc2d385de)

### Gallery
- Allows users to see more photographs that isn't included on the Facebook feed.

![Gallery](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/1f9d0633-c97e-4bff-8ad1-2c72c0121c66)

### Contact Page
- Allows users to contact me by sending a message that includes their name, email and the message they wrote. The Contact form is linked to a back-end service that stores all messages in an inbox for me to read. Whenever there's a new message, a notification will be sent to my email to notify me.

![Contact Form](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/325672e2-d14c-4e59-a68d-753afcf23ef9)
![Inbox](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/52c7dbeb-7382-4127-afcd-57203a717bd8)

## Design

### Color Scheme

I used a color scheme that matches with the colors on my logotype, it's also a good contrast and makes it easy to see and read what's on the screen.
- #ffffff - is used for the navigation bar and footer.
- #3a3a3a - is used for most of the text on the website.
- #29abe1 - is used for some of the text in the logo and headings.
- #add8e6 - background for the Contact form.
- #d3d3d3 - background color for the main content.

![Colorscheme 3](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/fe22ccfa-8d07-49a1-a8c3-de8857447ae9)

### Typography
Imported from Google Fonts.

- Cinzel - used for the logo, navigation bar, headings and footer.

![Google Fonts - Cinzel](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/de8622f5-6990-4300-a36f-bfb976f142cb)

- Fauna One - used for the title and description for the gallery cards, and for the placeholder text on the Contact form.

![Google Fonts - Fauna One](https://github.com/Humanslaughter/portfolio-project-1/assets/122393963/e17ab742-3689-4a8d-8654-0a9450445a5b)


## Testing

Testing was ongoing all throughout the development process. Chrome Dev Tools was used during the building to test the responsiveness, interaction, looks, and layouts for different screen sizes. The deployed website is tested on Chrome, Opera GX and Samsung S22 Ultra, looks and works as intended. I also had a friend of mine check out the website and he told me it looks and works well.
- Links<br>
  Each link workes as expected on every page, links leading to external pages opens correctly in a seperate browser tab.
- Contact Form<br>
  Works as expected. When all fields are filled in, the form get sent to the Ratufa back-end service and you get sent back to the home page. Ratufa sends me an email, notifying me that a new message has been submitted in the form. If you try to click send without filling in the required fields, it will display that those fields can't be empty.

### Validator Testing
- HTML [W3C](https://validator.w3.org/nu/)<br>
  No errors.
    - [Home](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhumanslaughter.github.io%2Fportfolio-project-1%2F)
    - [Gallery](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhumanslaughter.github.io%2Fportfolio-project-1%2Fgallery.html)
    - [Contact](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhumanslaughter.github.io%2Fportfolio-project-1%2Fcontact.html)

- CSS [Jigsaw](https://jigsaw.w3.org/css-validator/)<br>
  No errors.
    - [Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fhumanslaughter.github.io%2Fportfolio-project-1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

### Known Bugs
- There's a popup that will say "This form is not secure. Autofill has been disabled" when you click on any of the fields for the contact form. I have yet to find a solution for that.
- Logotype image, text, and form on the Contact page is very slightly more to the right on the page rather than centered when viewing on a 3440 x 1440 screen. I noticed it at the very end while doing some last edits, haven't been able to find what's causing it.

## Deployment & Local Development

Deployed via GitHub Pages:
  1. Navigate to the settings for the GitHub repository.
  2. On the menu to the left, click on "Pages".
  3. From the "Source" section drop-down menu under "Build and deployment", select "Deploy from a branch".
  4. From the section "Branch", select the options "main" and "/(root)" then click save.
  5. After you clicked save, the page will automatically refresh and a statement will be displayed stating the deployment was successful.

### Local Development

#### How To Fork

Fork the repository:<br>
	1. Log in/sign up to GitHub.
 	2. Go to the repository for this project [portfolio-project-1](https://github.com/Humanslaughter/portfolio-project-1).
	3. Click the 'Fork' button in the top right corner.

#### How To Clone

Clone the repository:<br>
	1. Log in/sign up to GitHub.
 	2. Go to the repository for this project [portfolio-project-1](https://github.com/Humanslaughter/portfolio-project-1).
	3. Click the code button, select which one you want to clone with (HTTPS, SSH or GitHub CLI) and copy the link shown.
 	4. Open the terminal in a code editor and change the current working directory to a location of your choice to use for the cloned directory.
	5. Type 'git clone' in the terminal, paste the link that you copied in step 3 and then press enter.


## Credits

### Content

- Gallery<br>
  Took some inspiration/help with the code from [ByteGrad](https://www.youtube.com/@ByteGrad)'s tutorial [Create Equal Height Cards Responsively with HTML & CSS Flexbox](https://www.youtube.com/watch?v=1qmBVcCjC9g&list=LL&index=40).
  
- Contact Form Design<br>
  Some of the CSS style code comes from [W3docs](https://www.w3docs.com)'s tutorial [How to Create Contact Form With CSS](https://www.w3docs.com/snippets/css/how-to-create-contact-form-with-css.html).
  
- Facebook Page Feed On Homepage<br>
  Script from [Juicer.io](https://www.juicer.io). The feed is linked to my Facebook page [Wikström Photography](https://www.facebook.com/wikstromphotos).
  
- Footer Icons - [Font Awesome](https://fontawesome.com)

- Back-End Service For Contact Form - [Ratufa.io](https://www.ratufa.io)

### Media
- All images is taken/made by me.
