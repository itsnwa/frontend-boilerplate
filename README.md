# Front-end Starter Kit

Opinionated from top to bottom.

# Getting Started

### Install all dependencies

`$ bundle install` and `$ npm install`

### Run local development server

Run `$ gulp` to start the server, a new browser window/tab automatically opens on `localhost:3000`

### Folder structure

The only folder you need to think about is the `./src` folder, all your content should go in here.
Make sure you follow the folder structure to ensure that all files get processed in the task runner.

```
front-end-starter-kit/
|
|- src/
|  |- index.html _____________________ # Entry point
|
|  |- scss/
|    |- main.scss ____________________ # Main SCSS file, only imports
|    |- partials/
|       |-  _base.scss________________ # Base styles
|       |-  _variables.scss___________ # Variables
|       |-  ..._______________________ # Add your own components here
|
|  |- images/
|     # Put all your images here, including content images
|
|  |- js/
|    |- main.js ______________________ # Main JS
```

# Based on

- jekyll
- gulp
- browsersync
- modernizer
- sass
- postcss
  - nextcss
  - autoprefixer
  - pxtorem
  - lost
- cssnano
- imagemin
- uglifyjs
