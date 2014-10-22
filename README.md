Portfolio Website V1

Build 1.0

NOTE

MAMP/WAMP or a PHP server such as https://github.com/sindresorhus/grunt-php is required to view all pages as the ".html" extension has been removed from all relative page links via the .htaccess file

Restoring the extension allows it to work on a defualt grunt server using the "grunt serve" command in the command line

Use the .htaccess file in the "app" folder because it has customization changes instead of the auto generated grunt version in the "dist" folder

.htaccess CHANGES
- 404 page - activated and custom
- url rewrite - for changing the links

Canonical Links - http://alexcican.com/post/how-to-remove-php-html-htm-extensions-with-htaccess/

Copy the sitemap.xml file as well

INSTALL OPTION 1

1. Download .zip from github
2. CD into the folder and run the command "npm install"
3. CD into the folder and run the command "bower install"
4. Replace existing folders and files with the ones on your computer
5. Run the command "git init" and set it up with the repo

INSTALL OPTION 2

1. Make a folder directory
2. Run "yo webapp" and install with bootstrap and Sass
3. Replace existing folders and files with the ones in this folder
4. Run the command "git init" and set it up with the repo







