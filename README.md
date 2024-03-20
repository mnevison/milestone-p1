# Mark.dev - Milestone Project 1

![AmIResponsive Image](assets\docs\amiresponsive-siteimage.jpg)

Visit the deployed site: [Mark.dev](https://sprightly-pastelito-a5781b.netlify.app/)

As someone who is wanting to progress forward in Tech, I heard many people speak about "portfolios" and how important they are when looking for jobs. I wanted to design myself a website that would give the user a bit of useful information about me, while also displaying my knowledge and abilities either through the site its self, or projects I outline within the pages of the site.

## Contents

- [User Experience](#user-experience-ux)
  - [User Stories](#user-stories)

* [Design](#design)

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

![Colours](assets\docs\colour-scheme.jpg)

However, early on in the development of the site I wanted a background image that would fulfil 2 roles:

1. Be "Techy".
2. Have a similar colour scheme to what I've picked.

I came across this on [Freepik](https://www.freepik.com/free-vector/matrix-style-binary-code-digital-falling-numbers-blue-background_24600855.htm#fromView=search&page=1&position=12&uuid=f3a21a98-cbd2-45e2-ba34-23210db7aaf8) and decided I would run with this as my background.

When I added the background, I ended up changing my colour pallet away from my original one and using a colour picker to target the colours of the background image.

In my css file I declared some custom variables for my colouring scheme that was implemented throughout the site. Since starting my course, I have been watching a lot of videos on css and this seems to be a fairly common practice among front-end developers. Having the ability to affect the styling across your whole site by just changing 1 variable is a very useful thing, and I feel it is likely going to be considered best practice for quite a lot of people.

* The 2 darker shades `#011F37` and `#06426F` were what I originally intended for "background" uses.

* I went with `#21A4F0` for my primary text colour.

* I later added a slightly lighter "alternative" text colour in `#B1D4E0`.

* There was also an RGBA variant of my primary background colour defined ```rgba(3, 46, 81, 0.5)``` into it's own function for use on backgrounds with text, as the opacity on this didn't have any impact on the text its self. Using the "opacity" function within css seemed to dull the text. 

![final-scheme](assets\docs\final-scheme.png)
