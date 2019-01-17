# Project Title - Template for Simple JS App with Webpack Build
Project description - This is a template for developing simple, single page html, css and vanilla Javascript applications.

## Installation
In your terminal:
1. `git clone https://< username >.github.com/< repo-name >.git`
2. `cd < project-folder >`
3. `npm i`

## Development
Open `index.html` in your editor's live server to see 'changes on save' as you develop your project. Please note the following points:
- Edit the `index.html` file in place.
- Develop your project and place any assests in the `src` folder.
- If you rename any folders the build will not work unless you also changes the relevant names in the `webpack.config.js` file.

## Build
- Run `npm run build` in your terminal. Webpack will transpile, autoprefix, minify and bundle your css, image, font, and javascript assests in the `build` folder.
- In `index.html` comment out/delete the css and js tags: 
```html
<!-- <link rel="stylesheet" href="../src/main.css"> -->
<!-- <script src="../src/app.js"></script> -->
```
- In `index.html` uncomment the bundle.min.js script:
```html
<script src="./bundle.min.js" defer></script>
```
- Upload/deploy the contents of the `build` folder to your site.

## Demo
Link to a build of the template: 
[Template site](https://link-url.com)






