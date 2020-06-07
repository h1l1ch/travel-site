# Clear View Escapes. Your clarity. One trip away!

**CSS** and **JavaScript** oriented project built using *Node.js* and multiple *npm dependencies*. Introduced me to the modern workflow environment and its core concepts: *Git* & *GitHib*, *SourceTree*, *mobile-first* approach etc.


## How to use

* **Jump to different sections** (*Our Beginning*, *Features*, *Testimonials*) using *navigation bar*. Also *appropriate section* **gets automatically selected** once is being scrolled to.

* **Press "Get in Touch"** or **"Get Started Today"** to call *modal*.

* Check **"Secret Area"** at the *footer*. To get *access to secret information* **type: "javascript"**.

* This website was built with **mobile-first approach** in mind. Its design is **super-responsive**, you must check its *mobile* and *tablet versions*.

## Project structure

* **/docs/** depository includes *deployment version* of the project. 

* **/app/** depository includes *index.html* file and *assets* folder, in which *development code* is located:

  * **/assets/images/** includes *all images* used in designing the website. *Desktop*, *mobile* and *tablet version* images are in this folder due to responsive design. 
  
  * **/assets/scripts/** includes all JavaScript modules. All of them are imported in **"/App.js"** file.
   
  * **/assets/styles/** includes all CSS modules. All of them are imported in **"/styles.css"** file.
       
* **/cloud-functions/** depository includes *cloud functions server side* code.

* **/.gitignore** is a list filled with exceptions for Git. Once the whole project is commited exceptions will be ignored. 

* **/webpack.config.js** - file includes *webpack configurations*.

* **/.package.json** and **/.package-lock.json** both keep the list of requirements, which allow npm to download all necessary dependencies for further successful project loading. 

## Things I've learned 

* How to **manually** set **webpack configuration**. 

* **Block Element Modifier** rule and other techniques for building *organized HTML*.  

* **Postcss-simple-vars**, **postcss-nested** and other plugins for building *super organized CSS*.

* How to contribute to the project via **Git** and **GitHub**: 

   * How to *create*, *commit*, *push*, *fetch* and *pull* **repos**. 
   
   * Also how **merge branches** and solve **merging conflicts**.

* How to leverage **babel** and **webpack**. Spent time to build the ruleset manually.

* **Mobile-first** approach. Moved from "top to the bottom". Developed the *mobile* web-design *first* and *desktop* design *second*.

* How to **deploy site** to the servers. *Netlify* is a great option.

* What are and how to use **cloud functions** using *Netlify* lambda functions to keep the *"secret"* code saved.

* How to test **API calls** using *Postman* app.

* How to do **responsive** and **lazy-loaded** images to optimize the perfomance and avoid loading "unnecessary" content.

 
 ## Built With

* [PostCSS Simple Vars](https://github.com/postcss/postcss-simple-vars) - allows to use variables inside CSS selectors.

* [PostCSS Nested](https://github.com/postcss/postcss-nested) - allows to build nested CSS blocks in hierarchical order akin to HTML and JavaScript.

* [PostCSS HexRGBA](https://www.npmjs.com/package/postcss-hexrgba) - plugin that adds shorthand hex methods to rgba() values. 

* [Autoprefixer](https://autoprefixer.github.io/) - plugin smartly adds all necessary prefixes before deployment.

* [LazySizes](https://afarkas.github.io/lazysizes/index.html) - plugin, which lazy-loads images thus optimizes the perfomance.

* [Netlify](https://www.netlify.com/) - allows to build fast fast websites. Also has its own cloud functions. 





## Authors

* **Philip Chislou** - *Final work* - [Philip Chislou](https://github.com/h1l1ch).
* **LearnWebCode** - *foundation* - [Brad Schiff](https://github.com/LearnWebCode).


## Acknowledgments

* Many thank to **Brad Schiff** for teaching me those core concepts, which allowed me to build this website.  
