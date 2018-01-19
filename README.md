# Hacker Earth Tutues - CSS Layouts with Flexbox and CSS Grids 
This project is code created as part of following the youtube tutorial series by HackerEarth.

## Usage
> This project was started by cloning the following [starter project](https://github.com/Christianq010/sass_starter_pack). It is a basic template for turning HTML5 templates on the web into projects I can edit with SASS and JS dependencies handled via bower.


### Tutorial
HackerEarth Youtube Channel [here](https://www.youtube.com/channel/UCYU6nvKyRYnE5kiG9JXkXpA)

* How to build complex layouts using CSS Flexbox and Grid part 1 - https://www.youtube.com/watch?v=Y7pT1zZLJb0/
* How to build complex layouts using CSS Flexbox and Grid part 2 - https://www.youtube.com/watch?v=Y7pT1zZLJb0/
* How to build complex layouts using CSS Flexbox and Grid part 3 - https://www.youtube.com/watch?v=Y7pT1zZLJb0/


## Installation

### [NPM](https://docs.npmjs.com/cli/install)
* Install the dependencies after cloning this project (gulp, gulp-sass, browser-sync)

```sh
$ npm install
```

### Bower
* Run `bower install`

### Run Server
This will watch your sass files, compile them and run your dev server at http://localhost:3000

```sh
$ npm start
```

### Troubleshooting
#### The `node-sass` Error
* Delete the `node_modules` folder installed via `npm install`
* Install node dependencies with `yarn install`
* Run `npm rebuild node-sass`
* Run with `gulp`.