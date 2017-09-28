# :zap: Gulp Boilerplate
<img align="right" height="200px" width="auto" src="https://cdn.worldvectorlogo.com/logos/gulp.svg" alt="Gulp Logo">

_Gulp_ is a **Task Runner** that runs on _Node_. The "program" _Gulp_ is installed via the command line through `npm`, the node package manager and is run on the runtime environment _Node_. There is no GUI, everything is controlled by a config file and commands via the command line interface.

_Gulp_ is a tool for automating common and time consuming task that we deal with every day when we develop. This repo is a starter kit with an already created config and folder structure.

The **master** branch of this repo is able to automatically detect changes in your `html`-files and `scss`-files and updated your browser with these changes so you don't have to reload. This config will also automatically convert your `scss`-files to regular `css`-files so there is no need to use `sass` command in your ruby-command line (`gulp-sass` actually uses `node-sass` which is a port of the original ruby gem that we used earlier). The config will also autoprefix your `css`-files.

## Instructions for the boilerplate

* Clone the repository.

* Use this command to install all dependencies for the project:

```bash
# Uses package.json "devDependencies" to install dependencies
npm install
```

* Start `gulp` by running:

```bash
npm start
```

* Write code in the `src`-folder.


## Folder structure

* `dist` - The converted files that are linked via `index.html`. You don't have to touch these files
    - `js` - All converted `js`-files go here
    - `css` - All converted `css`-files go here
* `src` - This is where your development-files are. There are the ones you work on
    - `js` - All unconverted `js`-files
    - `scss` - All unconverted `scss`-files
* `Gulpfile.js` - This config file must be in the root-folder
* `index.html` - The index must be in the root-folder
* `package.json` - All the dependencies and config for the project


## Branches

This repo has three different branches:

* **master**
    - Standard with `gulp-sass` and `browser-sync` that handles live-reloading and converting `sass` to prefixed `css`
* **babel**
    - Also has `gulp-babel`-module to transform ES6-code to older code that is accepted in older browsers.
* **browserify**
    - Has `browserify` and helper utilities to be able to use `import` and `export` in the browser.


## Dependencies used in this boilerplate

* [gulp](https://www.npmjs.com/package/gulp)
* [gulp-sass](https://www.npmjs.com/package/gulp-sass)
* [browser-sync](https://www.npmjs.com/package/browser-sync)
* [gulp-postcss](https://www.npmjs.com/package/gulp-postcss)
* [autoprefixer](https://www.npmjs.com/package/autoprefixer)
* [gulp-babel](https://www.npmjs.com/package/gulp-babel)
* [babel-preset-latest](https://www.npmjs.com/package/babel-preset-latest)
* [browserify](https://www.npmjs.com/package/browserify)
* [babelify](https://www.npmjs.com/package/babelify)
* [gulp-util](https://www.npmjs.com/package/gulp-util)
* [vinyl-source-stream](https://www.npmjs.com/package/vinyl-source-stream)


## Links

* [nodeschool.io | node tutorials](https://nodeschool.io/)
* [Gulp Tutorial](http://www.laminsanneh.com/blog/post/60/gulpjs-javascript-build-system-tutorial-beginners-and-advanced)
* [CSS-tricks | Gulp Tutorial](https://css-tricks.com/gulp-for-beginners/)
* [npmjs.com](https://www.npmjs.com/)