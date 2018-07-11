# Target
An assignment from internship to test html/css skills. 
The goal is to create a landing page with links to other sub-pages that is showing a task lists. There is no requirement of Javascript, or interactivity per se.

# Tools & Methodology
I was super excited to learn Sass and BEM methodology within this sample page. Except for that, I also include Normalize.css to unify the general setup across browsers. 

# Construction
The main css code is written in main.scss file under scss folder and export to static folder's main.css file. 

In the setting.scss, variables, mixins, templates and a base setup are all included.

As BEM infers to, all the class names are following its convention: block __ element -- modifier. Blocks refers to individual sections or page elements, thus it can be "main" or "about". Element includes "text", "title" etc.

In general, the responsiveness is introduced with mainly flexbox and a bit media query.
