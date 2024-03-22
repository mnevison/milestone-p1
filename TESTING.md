# Mark.dev - Milestone Project 1 - Testing

![AmIResponsive Image](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/amiresponsive-siteimage.jpg)

Visit the deployed site: [Mark.dev](https://sprightly-pastelito-a5781b.netlify.app/)

---

## Contents

- [Automated Testing](#automated-testing)

  - [W3 Validator - HTML](#w3-validator---html)
  - [W3 Jigsaw - CSS](#w3-jigsaw---css)
  - [Lighthouse](#lighthouse)

- [Manual Testing](#manual-testing)

  - [User Stories](#testing-user-stories)
  - [Full Site & Feature Testing](#full-site--feature-testing)
    - [Devices](#devices)
    - [Features](#features)

---

Testing was something I did throughout the build process. I leaned heavily on Google Dev Tools to help with responsive layout and getting the pages to look as I wanted them to and troubleshoot issues that arose.

I've tested the sites responsiveness across multiple browsers and devices to try and cover a wide range. I don't have access to any Apple based products, so my testing on Safari is limited.

---

## Automated Testing

### W3 Validator - HTML

[W3C Validator](https://validator.w3.org/) has been used to ensure the validity of the HTML markup across the project.

- [Index/Home](https://github.com/mnevison/milestone-p1/blob/ddd18638d990563bd3b3b20eff3bf24a66434161/testing/w3/home-w3.png) - Passed with no errors or warnings.
- [Experience](https://github.com/mnevison/milestone-p1/blob/c4acd944e06f9db976363adf68ed2a1355c68884/testing/w3/experience-w3.png) - Passed with no errors or warnings.
- [Projects](https://github.com/mnevison/milestone-p1/blob/c4acd944e06f9db976363adf68ed2a1355c68884/testing/w3/projects-w3.png) - Passed with no errors or warnings. I did need to go back to my HTML and troubleshoot some errors initially relating to a stray " left when I moved my .active class for my navbar styling.
- [Contact](https://github.com/mnevison/milestone-p1/blob/2f4658d5dfb6b8ac6d4c05e46f7bf57dd1ff6b55/testing/w3/w3-contact.png) - Passed with no errors or warnings. Needed to remove a mis-placed alt tag in response to initial errors on the page.

### W3 Jigsaw - CSS

[W3C Jigsaw](https://jigsaw.w3.org/css-validator/) was used to validated my CSS document(s). My project contains 2 files, a "global" one, which contains styles for elements that appear across each page and a regular style.css file. When providing a direct link to the site it will check all CSS files.

- [CSS](https://github.com/mnevison/milestone-p1/blob/de46a3b5fe080bcb6225bfa0ff55fc119d62551f/testing/w3/jigsaw-css.png) - No errors found.

### Lighthouse

I ran each page of my site through Lighthouse on Google Dev Tools to test the various performance metrics it measures. After my initial testing, I wasn't happy with my results so I went back into my HTML and worked on some of the feedback provided. I will display both before and after results below for each page on desktop & mobile devices.

_Lighthouse results range from 0-100. Ranges 0-49 are seen as "poor" 50-89 are considered good, and anything over 90 would be excellent. The changes I made to increase my scores regarding accessibility were done within my "footer" - my links were aria-hidden: true which causes issues for screen readers. I improved my SEO score by added more descriptive meta data within the head section of each page - basic description of the site and details of the author._

#### Desktop Results - Before

![Home-desktop](https://github.com/mnevison/milestone-p1/blob/5f08638f8091ca24aa4c2ecb7afa05ab8ef19586/testing/lighthouse/home-desktop.png)
![Experience-desktop](https://github.com/mnevison/milestone-p1/blob/5f08638f8091ca24aa4c2ecb7afa05ab8ef19586/testing/lighthouse/exp-desktop.png)
![Projects-desktop](https://github.com/mnevison/milestone-p1/blob/f7e72d00dd2c95ad063d08c72803dd892c530d7a/testing/lighthouse/projects-desktop.png)
![Contact-desktop](https://github.com/mnevison/milestone-p1/blob/815c1d35ffca7b2d0239e8053a9f1979c70cdded/testing/lighthouse/contact-desktop.png)

#### Desktop Results - After

![Home-after](https://github.com/mnevison/milestone-p1/blob/be6c2cd66f7507d1497ef67650d1b2af888d61be/testing/lighthouse/home-desktop-after.png)
![Experience-after](https://github.com/mnevison/milestone-p1/blob/be6c2cd66f7507d1497ef67650d1b2af888d61be/testing/lighthouse/exp-desktop-after.png)
![Projects-after](https://github.com/mnevison/milestone-p1/blob/be6c2cd66f7507d1497ef67650d1b2af888d61be/testing/lighthouse/projects-desktop-after.png)
![Contacts-after](https://github.com/mnevison/milestone-p1/blob/be6c2cd66f7507d1497ef67650d1b2af888d61be/testing/lighthouse/contact-desktop-after.png)

As you can see - the few minor changes increased my metrics pretty significantly.

#### Mobile Results - Before

![home-mobile](https://github.com/mnevison/milestone-p1/blob/815c1d35ffca7b2d0239e8053a9f1979c70cdded/testing/lighthouse/home-mobile.png)
![exp-mobile](https://github.com/mnevison/milestone-p1/blob/815c1d35ffca7b2d0239e8053a9f1979c70cdded/testing/lighthouse/exp-mobile.png)
![projects-mobile](https://github.com/mnevison/milestone-p1/blob/815c1d35ffca7b2d0239e8053a9f1979c70cdded/testing/lighthouse/projects-mobile.png)
![contact-mobile](https://github.com/mnevison/milestone-p1/blob/815c1d35ffca7b2d0239e8053a9f1979c70cdded/testing/lighthouse/contact-mobile.png)

#### Mobile Results - After

![home-mob-after](https://github.com/mnevison/milestone-p1/blob/67a466c2a8916fcd91985fa0be615741924fd659/testing/lighthouse/home-mobile-after.png)
![exp-mob-after](https://github.com/mnevison/milestone-p1/blob/67a466c2a8916fcd91985fa0be615741924fd659/testing/lighthouse/exp-mobile-after.png)
![project-mob-after](https://github.com/mnevison/milestone-p1/blob/67a466c2a8916fcd91985fa0be615741924fd659/testing/lighthouse/projects-mobile-after.png)
![contact-mob-after](https://github.com/mnevison/milestone-p1/blob/67a466c2a8916fcd91985fa0be615741924fd659/testing/lighthouse/contact-mobile-after.png)

Again - Pretty significant bump in the over-all metrics.

---

## Manual Testing

### Testing User Stories

**First Time Visitor Goals**

| Goals                                              | How are requirements met?                                                                                                                                                      |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| I want to get useful information about this person | I wanted to make sure the intent of the website was made clear on the home page, as well as provide some basic but useful information to a first time user.                    |
| I want the site to work on my chosen device        | I have tested the site across multiple different devices using either physical or responsive mode via Google Dev Tools                                                         |
| I want to find my way around the site easily       | Each page of the website, regardless of device has a dedicated navbar at the top of the page. The page title can also be interacted with to bring users back to the home page. |

**Returning Visitor Goals**

| Goals                                                              | How are requirements met?                                                                                                  |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------- |
| I want to be able to explore more of what this person has to offer | As users navigate around the site, they will uncover a wealth of information about me, my background, skills projects etc. |

**Frequent Visitor Goals**

| Goals                                                                   | How are requirements met?                                                                                                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| I want to have the option to reach out and communicate with this person | Someone that visits the page multiple times likely has an interest in what I might have to offer - I have specifically included a contact section so people can reach out either via email, phone or using one of the social links provided. I also added a form so that a user could get in contact to discuss project ideas. |

---

## Full Site & Feature Testing

### Devices

The site was built using VSCode on a desktop Windows based PC. When testing the site features and responsiveness I tried to use a range of devices I had at my disposal, as well as asking friends and peers to check the site.

Devices I used to check personally are:

- Primary Display

  - AOC 24" 1080p Monitor

- Laptop

  - Lenovo Thinkpad 14inch

- Mobile
  - Google Pixel 7
  - Google Pixel 7a
  - Google Pixel 6
  - Samsung s20

I tested the site using Google Chrome, Microsoft Edge and Firefox on the Desktop & Laptop. Mobile devices are running Chrome, and I was able to use the Samsung Browser on the s20.

_Unfortunately I don't know anyone who has a device that is part of the Apple ecosystem, so my testing on Apple products is LIMITED! I was however able to find a website <https://browserstack.com> that allowed me to emulate Safari for a very small amount of time. I took some screenshots of the process, however I was only allowed access for 2 minutes._

#### Resizing Desktop

![saf-fs](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/safar-fullscreen.png)
![saf-hs](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/safar-half.png)
![saf-smol](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/safar-smol.png)

#### Dev Tool View - All pages

![dev-home](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/dev-home.png)
![dev-exp](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/dev-experience.png)
![dev-project](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/dev-projects.png)
![dev-contact](https://github.com/mnevison/milestone-p1/blob/26618f274cb6c680bbdf27b7c13d5c22f72e5d4e/testing/safari/dev-contact.png)

_As you can see, the testing wasn't extensive. I was able to test all the links worked and the stylings all applied as intended._

---

## Features

### Header & Footer

The Header & Footer of the site are present on each page. Header will always be in view - this is more apparent on a mobile device as the colouring changes into a more solid colour as to allow it to always remain on top of the content when scrolling down the site. The footer remains on the bottom, as intended and contains useful social links.

**Testing**

| Feature                                | Expectation                                                                                         | Test Performed                      | Outcome                                                                     |
| -------------------------------------- | --------------------------------------------------------------------------------------------------- | ----------------------------------- | --------------------------------------------------------------------------- |
| Mark.dev Title                         | Navigate back to home                                                                               | Clicked link                        | Refreshed/Changed page                                                      |
| Nav Links                              | Take user to required page                                                                          | Clicked link                        | Went to intended page                                                       |
| Hover effect                           | Alter colour of a clickable link when hovering over                                                 | Hovered over                        | Changed colour                                                              |
| Header always on top on mobile devices | Header element and contents (title and navigation) remain on top of content                         | Screen resized & scrolled down page | Header was on top of contact and all interactions still present and working |
| Active Page                            | The page the user is on is to be highlighted in a different colour to the standard navigation links | Changed to each page                | Correct page was highlighted when viewing                                   |
| Footer Links                           | A new tab would open when link is pressed and user would be taken to desired page                   | Clicked links                       | New tab opened for each link provided                                       |

### Home Page/Index

The main feature of the home page would just be the general content. Ensuring that the content and especially the hero/profile image were responsive across all view ports was my main concern with this page.

**Testing**

| Feature            | Expectation                                      | Test Performed                          | Outcome                                                              |
| ------------------ | ------------------------------------------------ | --------------------------------------- | -------------------------------------------------------------------- |
| Responsive Content | Content resizes/rearranges based on users device | Tested across a range of devices/medias | Content changed size and remained legible across said devices/medias |

### Experience

As with the home page, this page is designed primarily with just raw content in mind, so the features are the same as the home page.

**Testing**

| Feature            | Expectation                                      | Test Performed                          | Outcome                                                              |
| ------------------ | ------------------------------------------------ | --------------------------------------- | -------------------------------------------------------------------- |
| Responsive Content | Content resizes/rearranges based on users device | Tested across a range of devices/medias | Content changed size and remained legible across said devices/medias |

### Projects

The Projects page is intended to give the user a look at what projects i'm working on/have worked on recently. I knew going into this page I wanted to use cards that stood out and looked the part while also providing all the information a user would need.

**Testing**

| Feature            | Expectation                                                                                                   | Test Performed                          | Outcome                                             |
| ------------------ | ------------------------------------------------------------------------------------------------------------- | --------------------------------------- | --------------------------------------------------- |
| Card Hover         | The card hovers when user would scroll over it                                                                | Hovered over card                       | Card hovered as intended                            |
| Project Links      | User can click the project link and a live deployed version of the project will open in a new tab for viewing | Clicked link                            | Taken to a deployed version of the selected project |
| Source Code Links  | User can click the link and be taken to the source code for the project, opened in a new tab                  | Clicked link                            | Taken to source code in a new tab                   |
| GitHub Link        | User can click the word "GitHub" on the screen and be taken to my GitHub page                                 | Clicked link                            | Taken to my GitHub page                             |
| Responsive Content | All content still viewable across all devices/medias                                                          | Tested across a range of devices/medias | Content resizes/wraps depending on the size         |

### Contact

The Contact page does as the name suggests - provides users with either contact information, or a way to contact me. This is done by either raw information or via the form.

**Testing**

| Feature        | Expectation                                                                                         | Test Performed                       | Outcome                                                                        |
| -------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------------------------------------------ |
| CV link (icon) | Click link and be redirected to a downloadable CV/resume                                            | Clicked link                         | New page opened in a new tab to the CV                                         |
| Icon hover     | Change colour when hovered over                                                                     | Hovered over icon                    | Icon changed colour                                                            |
| Contact Form   | User inputs information into the form and submits, gets a new window pop-up with an acknowledgement | Filled in form and hit submit button | Response opens in a new tab with intended message |


*Contact form previously contained the only known bug on the site - That has since been corrected. Full details of the bug are in [README.md](https://github.com/mnevison/milestone-p1/blob/4bd920ec002936b6b68026a1ef539873389bde4e/README.md)*