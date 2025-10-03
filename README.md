# Prevent Strategy

<img src="documentation\images\prevent-strategy.png">
<p align="center">
    <a href="https://ruon90.github.io/individual-project-1/" target="_blank">Live site</a>
</p>

## Introduction

This is my first individual project while completing the Code Institute full stack software developer bootcamp.

This project tasked us with creating a website using HTML, CSS and Bootstrap in order to satisfy the given brief within the timeframe.

I opted to do the prevent strategy website as I thought it would be more of a challenge, upon beginning research into the subject matter I realised most people referred to the Prevent program are teenagers, so I decided to make a website that would appeal to teenagers as well as having the information required for adults.

<h2 align="center" id="TOC">Table of contents</h2>

-   [Prevent Strategy](#prevent-strategy)
    -   [Introduction](#introduction)
    -   [Table of Contents](#TOC)
    -   [Project Outline](#project-outline)
-   [Project Planning](#project-planning)
    -   [UX Design](#ux-design)
        -   [User Stories](#user-stories)
        -   [Colours](#colours)
        -   [Fonts](#fonts)
        -   [Imagery](#imagery)
        -   [Wireframes](#wireframes)
-   [Features](#features)
    -   [General Features](#general-features)
        -   [Navigation and Hero Section](#navigation-and-hero-section)
        -   [Further information page](#further-information-page)
        -   [Bootstrap Cards](#bootstrap-cards)
        -   [Jumbotron](#jumbotron)
        -   [Modal Form](#modal-form)
        -   [Success page](#success-page)
        -   [Footer](#footer)
        -   [Links and Buttons](#links-and-buttons)
    -   [Responsive Design](#responsive-design)
-   [Built With](#built-with)
    -   [Technology and Languages](#technologies-and-languages)
    -   [Libraries and Frameworks](#libraries-and-frameworks)
    -   [Tools & Programs](#tools-and-programs)
-   [Development](#deployment)

    -   [Testing & Validation](#testing--validation)
    -   [AI](#ai)
    -   [Content Research](#content-research)

    -   [Summary](#summary)

## Project outline

### External user's goals:

Basic introduction to Prevent strategy, including how to recognize signs of radicalisation and how to report concerns presented in a simple, easy to navigate format.

### Site owner's goals:

Create an informative webpage that introduces the prevent strategy, content should be well organised and easy to digest, with a focus on simplicity and clarity through HTML and CSS with Bootstrap.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Project planning

Github projects and repo issues were used to create tasks from user stories, projectboard available <a href="https://github.com/users/Ruon90/projects/8/views/1" target="_blank">here</a>. I then decided on fonts, colour palette and

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## UX design

### User Stories

#### Must haves:

-   As a website owner I want my webpage to be informative and well organised and easy to digest. So that younger users can access the information easily but there’s also more substantial information for parents / professionals.

-   As a website owner I want my site to be focussed on simplicity So that everything is easy to find and read.

-   As a website user I want to be able to navigate the information easily So that I can find the relevant information quickly.

-   As a site user I can get a basic introduction to prevent strategy. So that I can understand what the strategy is and how it effects me.

-   As a website user I can learn how to report concerns in relation to the prevent strategy. So that I know where to go to raise any concerns to the relevant bodies.

-   As a website user I want to be able recognise the signs of radicalization So that I can report anything necessary.

#### Should haves:

-   As a website user I can get access to more comprehensive information that not all users would necessarily need or want. So that I can get all the relevant information from the website.

-   As a website user I can submit my details via a form to be kept up to date with news regarding prevent strategy So that I can keep informed on latest updates.

#### Could haves:

-   As a website user I can download a printable PDF file with the information from the site as a leaflet So that I can give information out to others.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Colours

The colour palette was chosen with AI, as the website target audience is younger the colour choices were based on a mixture of Twitch and Tik-Tok.

-   Background colour #1E1E2E (deep indigo, not pure black → softer)

-   Primary Accent: #2EE5A0 (minty green, fresh/optimistic)

-   Secondary Accent: #F72585 (bright magenta, energetic)

-   Highlight / Callout: #FFB703 (warm golden yellow for positivity)

-   Neutral Contrast: #F5F5F5 (light grey/white for text)
<p align="center">
<img src="documentation/images/Colour palette.png">
</p>
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Fonts

Fonts chosen from google font library.

-   Primary font : Kalam, with cursive fallback.

-   Secondary font : Patrick Hand also with cursive fallback.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Imagery

I felt imagery was very important with this site, as it's aimed at younger audiences it is image heavy with lots of bright flashes of colour and a series of cartoon characters to attract the eye.

On top of the images I have also implemented various hover effects and animations through the site as well as extensive CSS styling.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Wireframes

Wireframes were created at the start of planning and while they have served as a guide the end product deviates a lot from the wireframes as the design naturally progressed.

#### Mobile wireframes:

<p align="center">
<img src="documentation/images/wireframe-mob-small.png">
<img src="documentation/images/wireframe-mob-page-1.png">
<img src="documentation/images/wireframe-mob-page-2.png">
</p>
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

#### Desktop wireframes:

<p align="center">
<img src="documentation/images/wireframe-web-1.png">
<img src="documentation/images/wireframe-web-2.png">
</p>
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Features:

### General features:

Website brand image on navbar is the same as the Favicon that is used as the webpages icon in the browser.

### Navigation & Hero image

Navigation bar is built using bootstraps inbuilt navbar system however it has been heavily customised using CSS. There is a pink glow for the active link, a light green colour for inactive links and then a brighter green whenever they are hovered over, the navbar is set to a container.

<p align="center"><img src="documentation/images/navbar.png"></p>
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Further information page

The further information page was designed to house a lot of information without being overwhelming, although I didn't have enough time to refine the content there is still a lot of information on that page. In order to make it easier to navigate this information is conveyed using an accordion element from Bootstrap which has been customised using CSS.
gt

<p align="center"><img src="documentation/images/further-info.png"></p>

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Bootstrap Cards

Bootstrap cards have been used to display character images with brief descriptions, the cards have been used this way to catch the attention of a younger audience and with straight forward enough headings they should know what the image is depicting.

Cards have custom CSS styles applied as well as a scale transformation animation when hovered, this gives the appearance of the card glowing as it gets bigger.

<p align="center"><img src="documentation/images/boot-card.png"></p><p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Jumbotron

A Jumbotron has been used as an overlay on the hero image, it clearly states what the website is for and has two CTA's. The jumbotron also has its own styles added to give it a shadow and and slightly darker background.

<p align="center">
<img src="documentation/images/jumbotron.png"></p>

### Modal form

As policy surrounding anti terrorism is constantly changing I decided to add a form to register for a newsletter, the form is nested within a modal and has custom styling, each input is required and a success page comes up for verification.

<p align="center">
<img src="documentation/images/modal.png">
</p><p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Success page

The success page is a simple thank you and validation for submitting the form.

<p align="center">
<img src="documentation/images/success.png"></p><p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Footer

The footer has been designed with a company name embellished on the left and social link on the right, the social links have similar animation to the cards (ease scale transformation) and they change colour when hovered over.

<p align="center">
<img src="documentation/images/footer.png">
</p><p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Links and buttons

As explained with the navbar all links have custom CSS properties applied and the buttons also have a custom class, all with hover and click effects, all buttons are from two base types and reused for continuity.

<p align="center">
<img src="documentation/images/buttons.png">
</p><p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Responsive design

<p align="center">
<img src="documentation/images/m2-macbook-air-and-phone-mockup.png" width="50%" height="700px"><img src="documentation/images/apple-responsive-devices-mockup.png" width="50%" height="700px">
</p>
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Built with

### Tech and languages

This website is built using:

-   HTML5
-   CSS3
-   Javascript snippets (imported)

### Libraries

The libraries used for this site are:

-   Bootstrap
-   Google fonts
-   Fontawesome
-   Favicon
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Development

### Tools & programs

Tools and programs used for development:

-   ChatGPT
-   Gemini
-   Co-Pilot
-   Favicon
-   Krita
-   VS Code
-   Github
-   Mokkify
-   lighthouse
-   W3C Validators
-   Light Youtube embeds by @labnol

### Testing & Validation

Initial testing was done from the user perspective, then lighthouse was used to gauge performance and accessibility. W3C HTML and CSS validators were then used to ensure code was error free. Following on from that Webpagetest was used to gauge performance and loading times.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

### Optimisation

Alot of time has been spent optimising the performance of the site, large image size, load order and other factors were initially giving low performance scores on lighthouse (around 55 at one point) you can see the waterfall graph below and the wait time for the site to process.

<p align="center">
<img src="documentation/images/waterfall-1.png">
</p><p align="right"><a href="#prevent-strategy">Back To Top</a></p>
I proceeded to reduce the image overhead by resizing, reformatting to webp and compressing all files. I then further improved optimisation by adding a facade to the youtube embed, changing the load order in the code and tidying up any left over closing tags etc.

After doing this lighthouse gave the following scores.

<p align="center">
<img src="documentation/images/lighthouse-1.png" height="200px"> <img src="documentation/images/lighthouse-2.png" height="200px">
</p>
And the new waterfall chart is as follows.
<p align="center">
<img src="documentation/images/waterfall-2.png">
</p>
If you would like to view the full report please click <a href="https://www.webpagetest.org/result/251002_ZiDcAH_8RZ/" target="_blank">here</a>.
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## AI

AI has been used alot throught the completion of this project, AI helped pick the colour palette based on it's market dataset, all images have been AI generated even though some have required alot of editing to be usable, AI has been used to generate written content and condense resources down in order to focus my time on the design and coding of the website.

Whilst AI has been used for content and images, it has <strong>not</strong> been used in any capacity for coding, any error checking has been done manually using google if necessary.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Content research / references

Content was created using the following sources:

-   <a href="https://homeofficemedia.blog.gov.uk/2024/12/05/prevent-and-channel-factsheet-2024/" target="_blank">Prevent and Channel factsheet – 2024 – Home Office in the media</a>
-   <a href="https://fullfact.org/law/what-prevent-strategy/" target="_blank">What is the Prevent strategy? – Full Fact</a>
-   <a href="https://www.gov.uk/government/publications/prevent-strategy-2011" target="_blank">Prevent strategy 2011 - GOV.UK</a>
-   <a href="https://assets.publishing.service.gov.uk/media/5a78966aed915d07d35b0dcc/prevent-strategy-review.pdf" target="_blank">Prevent review</a>
-   <a href="https://www.counterterrorism.police.uk/what-we-do/counter-terrorism/prevent/" target="_blank">Prevent | Counter Terrorism Policing</a>
-   <a href="https://news.sky.com/story/what-is-prevent-and-why-is-the-anti-terrorism-programme-controversial-13323541" target="_blank">What is Prevent - and why is the anti-terrorism programme controversial? | UK News | Sky News</a>
-   <a href="https://democracy.hants.gov.uk/documents/s135906/2025-06-18%20EAP%20-%20Prevent%20presentation%20June%202025.pdf" target="_blank">PowerPoint Presentation</a>
-   <a href="https://www.libertyhumanrights.org.uk/fundamental/prevent/#:~:text=The%20Prevent%20Strategy%20is%20the%20Government%E2%80%99s%20flagship%20counter-extremism,at%20risk%20of%20committing%20terrorist%20acts%20and%20intervene." target="_blank">Prevent - Liberty</a>
-   <a href="https://www.bbc.co.uk/news/election-2017-40151991" target="_blank">Reality Check: What is the Prevent strategy? - BBC News</a>
-   <a href="https://cpdonline.co.uk/knowledge-base/safeguarding/what-is-prevent/" target="_blank">What is Prevent? | Prevent duty & who is responsible</a>
-   <a href="https://content.eastamb.nhs.uk/assets/What_is_Prevent_0529e8abe1.pdf" target="_blank">What_is_Prevent_0529e8abe1.pdf</a>
-   <a href="https://www.gov.uk/government/publications/new-definition-of-extremism-2024/new-definition-of-extremism-2024" target="_blank">New definition of extremism (2024) - GOV.UK</a>
<p align="right"><a href="#prevent-strategy">Back To Top</a></p>

## Summary

I think the project has gone well, I think an extra day would of been nice but I am also aware I have packed alot of features in that maybe weren't necessary.

I doubt I will continue this project primarily because it's the content that needs the biggest improvement as alot of the wording etc was AI generated and as such doesn't quite read as it should.

I think the website is well structured and I'm happy with the design aspect, there are definitely areas I can improve on and next time I certainly wont be making the mistake of not merging branches correctly.

<p align="right"><a href="#prevent-strategy">Back To Top</a></p>
