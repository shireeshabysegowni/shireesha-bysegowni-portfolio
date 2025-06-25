# Developer Portfolio 

<p align="center">
<img src="https://raw.githubusercontent.com/PhantomScript/asset-container/b26b0ebaaa13bec7fac796ee0b8296676df6ee0b/developer-portfolio/website.svg" alt="" width="450px"/>
</p>

## Want to create a professional portfolio but cannot figure out how to? Use Developer Portfolio and create your own personalised portfolio today! With multiple themes to choose from, our easily customisable, user friendly website is designed to cater to developers and freelancers alike.

<br />

## Table of Contents :scroll:
- [Sections](#sections-bookmark)
- [Demo](#demo-movie_camera)
- [Themes](#themes-art)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Folder Structure](#folder-structure-open_file_folder)
- [Usage](#usage-joystick)
- [Hosting](#hosting-globe_with_meridians)
- [SEO](#seo-spider)
- [Packages Used](#packages-used-package)
- [APIs Used](#apis-used-world_map)
- [Fonts and Images](#fonts-and-images-performing_arts)
- [Upcoming Features](#upcoming-features-construction)
- [Contributors](#contributors-man_technologistwoman_technologist)

<br /><br />


# Sections :bookmark:
- HOME
- ABOUT
- RESUME
    - EDUCATION
    - SKILLS
    - EXPERIENCE
    - PROJECTS 
    - Achievements <br />
- SERVICES 
    - TESTIMONIALS <br />
- BLOG
- CONTACTS 

<br /><br />

# Demo :movie_camera:
![](https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/demo.gif)
## View live demo [here](https://dev-portfolio-template.netlify.app/).

<br />

# Themes :art:
### Green :green_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/greenThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/greenThemeDark.png" width="48%" alt="">
</div>
<br />

### Black & White :black_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/bwThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/bwThemeDark.png" width="48%" alt="">
</div>
<br />

### Blue :large_blue_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/blueThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/blueThemeDark.png" width="48%" alt="">
</div>

<br />

### Red :red_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/redThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/redThemeDark.png" width="48%" alt="">
</div>

<br />

### Orange :orange_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/orangeThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/orangeThemeDark.png" width="48%" alt="">
</div>

<br />

### Purple :purple_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/purpleThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/purpleThemeDark.png" width="48%" alt="">
</div>

<br />

### Pink 

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/pinkThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/pinkThemeDark.png" width="48%" alt="">
</div>

<br />

### Yellow :yellow_circle:

<div style="display: flex; justify-content: space-between;">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/yellowThemeLight.png" width="48%" alt="">
    <img src="https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/themes/yellowThemeDark.png" width="48%" alt="">
</div>

<br /> <br />

# Installation :arrow_down:
### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

## Also check [this](https://reactjs.org/docs/create-a-new-react-app.html) out if you are new to react.

#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

<br />

# Getting Started :dart:
### Fork and Clone the repo

#### To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```
git clone hhttps://github.com/<YOUR GITHUB USERNAME>/developer-portfolio.git
cd developer-portfolio
```
### Install packages from the root directory
```
npm install
```
#### or
```
yarn install
```
### Start the development server
```
npm start
```
#### or
```
yarn start
```
<br /

# Usage :joystick:
### Customize your details for each component in `src/data` [folder](https://github.com/hhhrrrttt222111/developer-portfolio/tree/master/src/data).

Eg:
```javascript
export const headerData = {
    name: '-- YOUR NAME --',
    title: '-- YOUR TITLE --',
    desciption:'-- DESCRIPTION --',
    image: '-- IMAGE --',
    resumePdf: ''
}

// You can also import image and PDF from assets as shown below

import resume from '../assets/pdf/resume.pdf'
import profileImg from '../assets/png/profileImg'

export const headerData = {
    name: '-- YOUR NAME --',
    title: '-- YOUR TITLE --',
    desciption:'-- DESCRIPTION --',
    image: profileImg,
    resumePdf: resume
}
```

#### Data for each component is divided into respective files.
>#### Set website theme in [`src/data/themeData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/themeData.js) and choose your favourite font from [`src/App.css`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/App.css)

> #### About You - [`src/data/aboutData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/aboutData.js)

> #### Education details - [`src/data/educationData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/educationData.js) 

> #### Enter your Projects - [`src/data/projectsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/projectsData.js)

> #### Add your Skills - [`src/data/skillsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/skillsData.js)

> #### Experience - [`src/data/experienceData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/experienceData.js)

> #### Achievements - [`src/data/achievementData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/achievementData.js)

> #### Services - [`src/data/servicesData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/servicesData.js)

> #### Testimonials - [`src/data/testimonialsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/testimonialsData.js)

> #### Your Blogs and Articles - [`src/data/blogData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/blogData.js)

> #### Contact Details - [`src/data/contactsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/contactsData.js)

> #### Social Media Profiles - [`src/data/contactsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/socialsData.js)

```javascript
// EXAMPLE
export const educationData = [
    {
        id: 1,
        institution: '-- INSTITUTION NAME --',
        course: '-- COURSE NAME --',
        startYear: '2017',
        endYear: '2019'
    },
    //
]
```

### Instructions and format for each section can be found inside the data files.
<br />

## Setting Up Contacts form :envelope_with_arrow:
> ### Follow these [instructions](https://github.com/hhhrrrttt222111/developer-portfolio/wiki/Contacts) to connect contacts form with Google Sheet

<br />



# SEO :spider:
### Search engine optimization (SEO) is the process of improving the quality and quantity of website traffic to a website or a web page from search engines. 
### Add the below code snippet to `public/index.html` with your site info. This step is not mandatory

<br />

```html
    <meta name="description" content="--- SITE DESCRIPTION ---" />
    <meta property="og:image" content="--- YOUR IMAGE ---">
    <meta property="og:site_name" content="--- YOUR NAME ---"/>
    <meta property="og:title" content="--- YOUR NAME ---"/>
    <meta property="og:url" content="--- YOUR SITE URL ---"/>
    <meta property="og:type" content="website"/>
    <meta property="og:description" content="--- SITE DESCRIPTION ---"/>
    <meta property="og:locale" content="---  ---">
    <meta property="og:image" content="--- YOUR IMAGE ---"/>
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    
    <meta itemprop="name" content="--- YOUR NAME ---"/>
    <meta itemprop="url" content="--- YOUR SITE URL ---"/>
    <meta itemprop="description" content="--- SITE DESCRIPTION ---"/>
    <meta itemprop="thumbnailUrl" content=""/>
    <link rel="image_src" href="--- YOUR IMAGE ---"/>
    <meta itemprop="image" content="--- YOUR IMAGE ---"/>
    
    <meta name="twitter:site" content="@--- YOUR TWITTER USERNAME ---">
    <meta name="twitter:creator" content="@--- YOUR TWITTER USERNAME ---">
    <meta name="twitter:url" content="--- YOUR SITE URL ---"/>
    <meta name="twitter:title" content="--- YOUR NAME ---">
    <meta name="twitter:description" content="--- SITE DESCRIPTION ---">
    <meta name="twitter:image" content="--- YOUR IMAGE ---">
    <meta name="twitter:card" content="summary"/>

```

<br />

# Packages Used :package:

| Client Side Packages  |
| :-------------: |
| @material-ui/core  |
| @material-ui/icons  |
| axios |
| react-fast-marquee |
| react-helmet  |
| react-icons  |
| react-reveal |
| react-router-dom  |
| react-router-hash-link  |
| react-slick  |
| slick-carousel |
| validator |


<br />

# APIs Used :world_map:
- [SheetDB](https://sheetdb.io/)


<br />

# Fonts and Images :performing_arts:

## Illustrations
- [Icons8](https://icons8.com/illustrations/styles)
- [SVG Porn](https://svgporn.com/)

## Icons
- [Material Icons](https://material-ui.com/components/material-icons/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Fonts
- [Poppins](https://fonts.google.com/specimen/Poppins)
- [Montserrat](https://fonts.google.com/specimen/Montserrat)
- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Big Shoulders Text](https://fonts.google.com/specimen/Big+Shoulders+Text)
- [Bestermind](https://www.dafont.com/bestermind.font)
- [Roboto](https://fonts.google.com/specimen/Roboto)

<br />