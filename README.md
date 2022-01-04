# Personal blog

---
## For what?

Personal blog for landing on CMS.

## Application launch.

In the root folder of the project, launch the terminal and run the command "npm install".
Run the "gulp" command to run the project on the local server.
Execute the "gulp build" command, this will create a folder with ready-to-deploy and minimized project files along the path "./assets/build".

## File structure. How to change. 

All source files are located in the path "./assets/src".
The *img* folder is intended for storing images, and *fonts* for fonts.
The *js* folder stores JS scripts.

### Styles.

All styles are located in the *style* folder. All styles are connected in the *main.css* file (if you have created a new file, it **must** be connected in main.css).
* *mixins.css* designed for mixins
* *variables.css* - for variables
* *my.css* - your main style file (already connected in main)
The *blocks* folder contains styles for individual code blocks.

### Markup.

In the *src* folder, all files with the *.html* extension represent the markup of the main pages of the site. The *template* folder contains frequently used markup templates.
Markup templates can be connected in another markup file using the construction - **//= [template path]**

## Technologies used.

* HTML
* SCSS
* Js
* Gulp