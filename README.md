# Resume

💼 Free resume page template with bulma css forked from https://github.com/mazipan/bulma-resume-template

## Live Demo

+ Dark Theme: [Resume](https://surenderlohia.github.io/resume/)

## For Devlopment

### Fork or Clone the repository

### Naviaget to repository

```
cd resume
```

### Install dependencies
```
yarn install
```
or
```
npm install
```

### To start development mode

```
npm run dev
```
It will start the local server: http://localhost:8080/ and listen for changes. 

### To build production version
```
npm run dist
```

### To publish to github pages
```
npm run publish-demo
```
Note: before publish edit `homepage` and `repository.url` in package.json

## Feature

+ Hot Module Replacement (HMR) in local development
+ Optimized assets (HTML minified, CSS purge and minified, JS minified)
+ Easy to update content
+ Available in light and dark theme version
+ Mobile friendly interface
+ Lightning speed load time performance

## Screenshoot

|              Dracula Theme          |
| :---------------------------------: |
| ![Dracula](screenshoot-dracula.png) |

## Lighthouse Audit

![Audit](screenshoot-lighthouse.png)

## Update with your own!

Just go and update [data.js](https://github.com/surenderlohia/resume/blob/master/src/data.js) file with your own data.

Below is the sample structure of data.js file:

```javascript
module.exports = {
    profile: {
        name: 'Surender Lohia',
        title: 'Frontend Developer',
        photo: 'https://avatars1.githubusercontent.com/u/6301437?s=460&v=4', // 300x300px
        city: 'Bangalore, India',
        website: 'https://www.surender.net/',
        phone: '9551800431',
        mail: 'surender.lohia.e@gmail.com'
    },
    social: {
        twitter: {
            name: '@surender_lohia',
            link: 'https://twitter.com/surender_lohia'
        },
        linkedin: {
            name: 'in/surenderlohia',
            link: 'https://www.linkedin.com/in/surenderlohia'
        },
        github: {
            name: 'surenderlohia',
            link: 'https://github.com/surenderlohia'
        }
    },
    summary: `Producing quality apps, focusing on writing eloquent and maintainable code. Working on Front-end, JavaScript, and Mobile App for large Scale applications.`,
    experiences: [{
            company: 'ThoughtWorks',
            location: 'Bangalore',
            title: 'Frontend Developer',
            period: 'MAY 2018 - MAR 2020',
            jobdesc: [
                'Responsibility to develop large scale application. Coordinate with designer, back-end devs and BA. Front-end tech stack HTML5, CSS3, JavaScript, Sass, React, Redux, Webpack, Npm, Jest.'
            ],
        },
        {
            company: 'Tenmiles',
            location: 'Chennai',
            title: 'Frontend Developer',
            period: 'JUN 2015 – MAY 2018',
            jobdesc: [
                'Front End and JavaScript development for large scale chat application. Front-end tech stack HTML5, CSS3, JavaScript, Sass, BackboneJS, jQuery, React'
            ],
        },
        {
            company: 'Fantain Sports',
            location: 'Chennai',
            title: 'Frontend Developer',
            period: 'JAN 2014 – MAY 2015',
            jobdesc: [
                'Mobile Application Front-end and JavaScript Development for large scale application. Front-end tech stack HTML5, CSS3, JavaScript, Knockout JS, Require JS, Sass, and Cordova.',
            ],
        },
        {
            company: 'Rage Communications',
            location: 'Chennai',
            title: 'Frontend Developer',
            period: 'OCT 2012 – DEC 2013',
            jobdesc: [
                'Front End Web development with Web Standards and Cross browser compatibility. Coordinate with designer and Back-End team. Front-end tech stack HTML, CSS, JavaScript, jQuery.',
            ],
        },
        {
            company: 'Sam-Sys',
            location: 'Chennai',
            title: 'Frontend Developer',
            period: 'AUG 2011 – SEP 2012',
            jobdesc: [
                'Front End Web development with Web Standards and Cross browser compatibility. Coordinate with designer and Back-End team. Front-end tech stack HTML, CSS, JavaScript, jQuery, Sass.'
            ]
        }
    ],
    educations: [{
        name: 'C.Kandhaswami Naidu College for Men',
        city: 'Chennai',
        degree: 'Bachelor Degree',
        faculty: 'Bachelor of Computer Application'
    }],
    projects: [{
            title: 'World Movies',
            company: 'Open Source Project',
            link: 'http://world-movies.surge.sh/#/',
            description: 'A simple movie listing app. A demo app created for cypress workshop.'
        },
        {
            title: 'Html Boilerplate',
            company: 'Open Source Project',
            link: 'https://www.surender.net/html-boilerplate/',
            description: 'A simple boilerplate code for html | Html boilerplate | html hello world | html starter kit'
        },
        {
            title: 'HappyFox Chat',
            company: 'HappyFox',
            link: 'https://happyfoxchat.com/',
            description: 'HappyFox Chat is a live chat application. My responsibility is Front-end development, using HTML5, CSS3, JavaScript, Sass, Backbone.js, React.js.'
        }
    ],
    skills: [{
            name: 'JavaScript',
            category: 'js'
        },
        {
            name: 'CSS',
            category: 'css'
        },
        {
            name: 'HTML',
            category: 'html'
        },
        {
            name: 'Sass',
            category: 'css'
        },
        {
            name: 'JQuery',
            category: 'js'
        },
        {
            name: 'React',
            category: 'js'
        },
        {
            name: 'Vue.js',
            category: 'js'
        },
        {
            name: 'Angular',
            category: 'js'
        },
        {
            name: 'Knockout.js',
            category: 'js'
        },
        {
            name: 'Backbone.js',
            category: 'js'
        },
        {
            name: 'Gulp',
            category: 'tool'
        },
        {
            name: 'Npm',
            category: 'tool'
        },
        {
            name: 'Webpack',
            category: 'tool'
        },
        {
            name: 'Mocha',
            category: 'tool'
        },
        {
            name: 'Jest',
            category: 'tool'
        },
        {
            name: 'Cypress',
            category: 'tool'
        },
        {
            name: 'Git',
            category: 'tool'
        },
        {
            name: 'Unix',
            category: 'tool'
        },
        {
            name: 'Jekyll',
            category: 'tool'
        },
        {
            name: 'Bulma',
            category: 'css'
        },
        {
            name: 'Semantic UI',
            category: 'css'
        },
        {
            name: 'Material UI',
            category: 'css'
        },
        {
            name: 'Twitter Bootstrap',
            category: 'css'
        },
        {
            name: 'Responsive',
            category: 'tech'
        },
        {
            name: 'Mobile Web App',
            category: 'tech'
        },
        {
            name: 'PWA',
            category: 'tech'
        },
        {
            name: 'Node.js',
            category: 'language'
        },
        {
            name: 'Python',
            category: 'language'
        },
        {
            name: 'Php',
            category: 'language'
        },
        {
            name: 'Express.js',
            category: 'backend-framework'
        },
        {
            name: 'Django',
            category: 'backend-framework'
        },
        {
            name: 'Wordpress',
            category: 'backend-framework'
        },
        {
            name: 'SQLite',
            category: 'database'
        },
        {
            name: 'MongoDB',
            category: 'database'
        },
    ],
    hobbies: [
        'Reading',
        'Coding',
        'Cycling',
        'Travelling'
    ]
}
```

-----

Copyright © 2020 by Surender Lohia
