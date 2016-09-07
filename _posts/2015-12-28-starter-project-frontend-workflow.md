---
title: "A Starter Project Using GulpJS"
layout: post
image: gulpjs.jpg
comments: true
comments_id: "starter-project-gulpjs"
---

## System Preparation
To use this starter project, you'll need the following things installed on your machine:

1. [NodeJS](http://nodejs.org) - (use the installer)
2. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install gulp -g` (run in console) (mac users might need sudo)


## Local Installation
1. Clone this [REPO](https://github.com/syahmifauzi/gulpjs-html-js-sass-minify-autoprefixer-browser-sync) or download it into a directory of your choice on your machine.
2. In console, `$ cd ` inside the directory, then run `$ npm install`.


## Usage:
_**Development Mode**_   
In console, run: `$ gulp`   

This will run:

1. browser-sync - (it will auto open your default browser and provide you a server)
2. file watching - (do everything for you as you save your file in 'app/')

_**Production Mode**_   
In console, run: `$ gulp build`

This will:

1. Build your production files such as html, css, js n others inside 'dist/' folder..   

If you found an error in console when building for production,    
try run `$ gulp clean` before `$ gulp build`

> `$ gulp clean` will delete 'dist/' folder and,   
> `$ gulp build` will build it again even though it will reclean first.. hmm.. nevermind..


## Folder Structure
After running `$ gulp` in console, the initial folder structure might look like this..

```
|- app/
    |- fonts/
    |- images/
    |- sass/
      |- style-main.scss
      |- variables.scss
    |- js/script-main.js
    |- index.html
|- dist/
    |- css/style-main.css
    |- js/script-main.js
    |- index.html
|- node_modules/
|- .gitignore
|- gulpfile.js
|- package.json
|- README.md
```

Run `$ gulp build` in console for distribution..
All files for distribution will be build in 'dist/' folder..
CSS &amp; JS files will be minified..

![Description](/assets/img/blogpost/anime.gif)

*Sorry, I'm newbie, trying to Gulp but end up writing ugly code.. Urgh!*   
*You may playing with code inside gulpfile.js as you wish..*
