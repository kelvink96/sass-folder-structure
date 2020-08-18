# sass-folder-structure

sass/ <br>
|-- abstracts/ (or utilities/) <br>
|-- base/ <br>
|-- components/ (or modules/) <br>
|-- layout/ <br>
|-- pages/ <br>
|-- themes/ <br>
|-- vendors/ <br>
| main.scss (or main.sass)

<h3>Definitions </h5>
### <b>Abstracts (or utilities)</b> <br> Holds Sass tools, helper files, variables, functions, mixins and other config files. These files are meant to be just helpers which don’t output any CSS when compiled. <br>
- <b>Base</b>: holds the boilerplate code for the project. Including standard styles such as resets and typographic rules, which are commonly used throughout your project. <br>
- <b>Components (or modules)</b>: holds all of your styles for buttons, carousels, sliders, and similar page components (think widgets). Your project will typically contain a lot of component files — as the whole site/app should be mostly composed of small modules. <br>
- <b>Layout</b>: contains all styles involved with the layout of your project. Such as styles for your header, footer, navigation and the grid system. <br>
- <b>Pages</b>: any styles specific to individual pages will sit here. For example it’s not uncommon for the home page of your site to require page specific styles that no other page receives. <br>
- <b>Themes</b>: this is likely not used in many projects. It would hold files that create project specific themes. For example if sections of your site contain alternate color schemes. <br>
- <b>Vendors</b>: contains all third party code from external libraries and frameworks — such as Normalize, Bootstrap, jQueryUI, etc. However, there is often a need to override vendor code.  <br>

