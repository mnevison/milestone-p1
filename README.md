# Mark.dev - Milestone Project 1

![AmIResponsive Image](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/amiresponsive-siteimage.jpg)

Visit the deployed site: [Mark.dev](https://sprightly-pastelito-a5781b.netlify.app/)

As someone who is wanting to progress forward in Tech, I heard many people speak about "portfolios" and how important they are when looking for jobs. I wanted to design myself a website that would give the user a bit of useful information about me, while also displaying my knowledge and abilities either through the site its self, or projects I outline within the pages of the site.

## Contents

- [User Experience](#user-experience-ux)
  - [User Stories](#user-stories)

* [Design](#design)
  - [Colour Scheme](#colour-scheme)
  - [Typography](#typography)
  - [Imagery](#imagery)
  - [Wireframes](#wireframes)
  - [Features](#features)
    - [Homepage](#home-page)
    - [Experience](#experience)
    - [Projects](#projects)
    - [Contact](#contact)
    - [Site Wide](#site-wide)

---

## User Experience (UX)

### User Stories

#### First Time Visitor Goals

- I want to get useful information about this person.
- I want the site to work on my chosen device.
- I want to find my way around the site easily.

#### Returning Visitor Goals

- I want to be able to explore more of what this person has to offer.

#### Frequent Visitor Goals

- I want to have the option to reach out and communicate with this person.

---

## Design

### Colour Scheme

As the page is meant to be a personal profile, I went with my favourite colour. With that as my starting point, I went to Google to try and find a resource that would give me an idea about good colour combinations. I found [Canva](https://www.canva.com/colors/color-palettes/), which had more than enough potential to pick something that popped for me.

Initially I settled on the "Window Tide" scheme.

![Colours](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/colour-scheme.jpg)

However, early on in the development of the site I wanted a background image that would fulfil 2 roles:

1. Be "Techy".
2. Have a similar colour scheme to what I've picked.

I came across this on [Freepik](https://www.freepik.com/free-vector/matrix-style-binary-code-digital-falling-numbers-blue-background_24600855.htm#fromView=search&page=1&position=12&uuid=f3a21a98-cbd2-45e2-ba34-23210db7aaf8) and decided I would run with this as my background.

When I added the background, I ended up changing my colour pallet away from my original one and using a colour picker to target the colours of the background image.

In my css file I declared some custom variables for my colouring scheme that was implemented throughout the site. Since starting my course, I have been watching a lot of videos on css and this seems to be a fairly common practice among front-end developers. Having the ability to affect the styling across your whole site by just changing 1 variable is a very useful thing, and I feel it is likely going to be considered best practice for quite a lot of people.

- The 2 darker shades `#011F37` and `#06426F` were what I originally intended for "background" uses.

- I went with `#21A4F0` for my primary text colour.

- I later added a slightly lighter "alternative" text colour in `#B1D4E0`.

- There was also an RGBA variant of my primary background colour defined `rgba(3, 46, 81, 0.5)` into it's own function for use on backgrounds with text, as the opacity on this didn't have any impact on the text its self. Using the "opacity" function within css seemed to dull the text.

![final-scheme](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/final-scheme.png)

## Typography

I used Google Fonts for the text across the entire site.

- The font I used was [Poppins](https://fonts.google.com/specimen/Poppins?preview.text=Mark.dev). The font is very clean, very rounded and gives off friendly vibes. It has excellent readability across all the font sizes and weights across the site.

![Poppins](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/Poppins-font.png)

## Imagery

- The background image I originally intended on using was removed towards the end of development, as it was suggested to be quite busy and caused issues with readability. Even though it is removed, it will feature in various images of the site, so this is a small sample of it.

![background-image](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/bg-snippet.jpg)

I maintained the colour scheme that the background inspired even after removal.

- I included a profile image/hero image. This image was AI generated.

- I used Fontawesome across the site to include brand logos.

## Wireframes

Wireframes were created for various devices using Balsamiq

![desktop-wf](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/main-wf.png) ![tablet-wf](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/tablet-wf.png) ![mobile-wf](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/mobile-wf.png)

## Features

The website is set across 4 pages, made up of a Home page, an Experience page, a Projects page and a Contact page.

Each page is responsive across a range of popular devices.

- Each page features a Favicon in the browser tab

![favicon](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/favicon-preview.png)

- The title of the page is displayed site wide and is also used to navigate back to the home page.

![home-title](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/title-preview.png)

### Home Page

The home page displays key information about the site and it's intended function. It provides basic information at a glance that is expended on the further into the site you go.

![home-pg](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/amiresponsive-siteimage.jpg)

### Experience

The experience page doubles down on some of the information provided in the home page, expanding on it and providing a lot more detail. This section of the site is intended to provide viewers with an overview of my past and present experiences, as well as going into further details about skills.

![experience-pg](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/experience-prev.png)

### Projects

The projects page is intended to highlight and display the projects I would consider to be most note worthy. Each card has a brief description of the project, as well as icons outlining what languages/technologies have been used to make it. Links are provided to a live version of the project as well as the source code. I also included a link to my GitHub for a complete overview.

![projects-pg](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/projects-prev.png)

#### Contact

This page does what it says on the tin - it provides users with my contact information. I added a form as well which can be used to get in contact with a possible project idea. I also provided a link to a downloadable version of my CV/Resume.

![contact-pg](https://github.com/mnevison/milestone-p1/blob/main/assets/docs/contact-prev.png)

### Site Wide

Each page within the site has a dedicated navbar and a footer. The navbar is responsive and changes depending on the screen size. The footer contains links to my various social accounts.
