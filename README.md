# Portfolio Website 2011 - 2017

![Portfolio Website 2011 - 2017](https://res.cloudinary.com/d74fh3kw/image/upload/v1582387258/portfolio_2011_2017_h2jfl9.jpg "Portfolio Website 2011 - 2017")

This app uses an outdated codebase follow the Quick Setup intructions if you want to see the app running locally with little effort.

## Quick Setup

1. Download/clone the repo
2. Use a static file server like [Zeit Serve](https://github.com/zeit/serve) and serve the folder dist_local

## Deprecated Information

A static server or a PHP server such as [grunt-php](https://github.com/sindresorhus/grunt-php) is required to view all pages as the ".html" extension has been removed from all relative page links via the .htaccess file

Restoring the extension allows it to work on a defualt grunt server using the "grunt serve" command in the command line

Use the .htaccess file in the "app" folder because it has customization changes instead of the auto generated grunt version in the "dist" folder

.htaccess CHANGES

- 404 page - activated and custom
- url rewrite - for changing the links

[Canonical Links](http://alexcican.com/post/how-to-remove-php-html-htm-extensions-with-htaccess/)

Copy the sitemap.xml file as well

Local Development Enviroment Prerequisites

- Ruby
- Sass
- Node.js
- npm
- git

Local Repo INSTALL OPTION 1 (WARNING Commits will be lost)

1. Download .zip from github
2. CD into the folder and run the command "npm install"
3. Run the command "bower install"
4. Run the command "git init" and set it up with the repo
5. Run the command "grunt serve" to make sure it is working

Local Repo INSTALL OPTION 2 (Clean Install with commits)

1. Make a folder directory
2. Run "yo webapp" and install with bootstrap and Sass
3. Replace existing folders and files with the ones in the MASTER
4. Run the command "grunt serve" to make sure it is working
