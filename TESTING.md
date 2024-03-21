# Mark.dev - Milestone Project 1 - Testing

![AmIResponsive Image](https://github.com/mnevison/milestone-p1/blob/d3d03dfae777b889387c4d5babbb8194158b123d/assets/docs/amiresponsive-siteimage.jpg)

Visit the deployed site: [Mark.dev](https://sprightly-pastelito-a5781b.netlify.app/)

---

## Contents

- [Automated Testing](#automated-testing)

  - [W3 Validator - HTML](#w3-validator---html)
  - [W3 Jigsaw - CSS](#w3-jigsaw---css)
  - [Lighthouse](#lighthouse)

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

*Lighthouse results range from 0-100. Ranges 0-49 are seen as "poor" 50-89 are considered good, and anything over 90 would be excellent. The changes I made to increase my scores regarding accessibility were done within my "footer" - my links were aria-hidden: true which causes issues for screen readers. I improved my SEO score by added more descriptive meta data within the head section of each page - basic description of the site and details of the author.*

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