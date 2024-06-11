#[AA• Design  System]

**[AA• Design  System]** is a responsive Bootstrap 4 kit provided for free by AA. It is a beautiful cross-platform UI kit.


##Bootstrap 4 Support

AA• Design System is built on top of the much awaited Bootstrap 4. This makes starting a new project very simple.


##Getting Started

I've also included an optional Gulp file to help you get started with theme customization. You'll need to install Node.js and Gulp before using our included gulpfile.js.

1. Download the project's zip
2. Make sure you have node.js (https://nodejs.org/en/) installed
3. Type `npm install` in terminal/console in the source folder where `package.json` is located
4. You will find all the branding colors inside `assets/scss/aa-design-system/custom/_variables.scss`. You can change them with a `HEX` value or with other predefined variables.
5. Run in terminal `gulp compile-scss` for a single compilation or `gulp watch` for continous compilation of the changes that you make in `*.scss` files. This command should be run in the same folder where `gulpfile.js` and `package.json` are located
6. Run in terminal `gulp default` for opening the Dashboard Page (default) of the product.


##File Structure

Within the download you'll find the following directories and files:

```
AA• Design System
.
├── README.md
├── assets/
│   ├── css/
│   │   ├── aa-design-system.css
│   │   ├── aa-design-system.css.map
│   │   ├── aa-design-system.min.css
│   │   └── nucleo-icons.css
│   ├── fonts/
│   ├── img/
│   ├── js/
│   │   ├── aa-design-system.js
│   │   ├── aa-design-system.js.map
│   │   ├── aa-design-system.min.js
│   │   ├── core/
│   │   │   ├── bootstrap.min.js
│   │   │   ├── jquery.min.js
│   │   │   └── popper.min.js
│   │   └── plugins/
│   └── scss/
│       ├── aa-design-system/
│       │   ├── bootstrap/
│       │   │   ├── mixins/
│       │   │   └── utilities/
│       │   └── custom/
│       │       ├── cards/
│       │       ├── mixins/
│       │       ├── sections/
│       │       ├── utilities/
│       │       └── vendor/
│       └── aa-design-system.scss
├── examples/
│   ├── profile-page.html
│   ├── landing-page.html
│   └── register-page.html
├── gulpfile.js
├── index.html
└── package.json
#
