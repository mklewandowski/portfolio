# portfolio
A portfolio of my professional work. This project is based on [Dopefolio](https://github.com/rammcodes/Dopefolio). The live version is hosted on GitHub Pages: [https://mklewandowski.github.io/portfolio/](https://mklewandowski.github.io/portfolio/)

## Running Locally
Use the following steps to run locally:
1. Clone this repo
2. run `npm install` to install dependencies
3. run `npm run compile:scss` to update CSS
4. open `index.html` in browser

## Build and Deploy to GitHub Page
Before we can deploy to a GitHub page, we first do the following setup (from [https://github.com/gitname/react-gh-pages](https://github.com/gitname/react-gh-pages)):
- install `gh-pages`: `npm install gh-pages --save-dev`
- add `homepage` property to `package.json`: `"homepage": "https://mklewandowski.github.io/portfolio/",`
- add `deploy` and `predeploy` properties to the `scripts` property of `package.json`

To deploy the current version:
- copy `assets`, `css`, `favicon.ico`, `index.js`,  and `index.html` into `build` folder
- run `npm run deploy`

## Development Tools
- Code edited using Visual Studio Code