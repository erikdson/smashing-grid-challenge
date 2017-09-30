# Smashing Magazine CSS Grid challenge

This is my attempt at the CSS grid challenge from Smashing Magazine. The website previews the upcoming football game between FC Barcelona and Real Madrid. The layout is build with many different techniques with fallbacks to make the website usable in older browsers such as Internet Explorer 8 and 9.

[Check out the result right here!](https://erikdson.github.io/smashing-grid-challenge/)

## Instructions for the website

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
