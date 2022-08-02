# Getting Started

You are currently reading the WTS Interactive Map documentation. This documentation has been written to help you regarding each step of setup and customization. Please go through the documentation carefully to understand how this software is made and how to edit this properly. HTML CSS, and JS knowledge is required to customize this software.

The software uses:

* webpack via [webpack](https://webpack.js.org/)
* ES6 via [babel](https://babeljs.io/) (v7)
* SASS via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)
* Node.js (v14+) development environment
* JQuery (v3.5.1) [jQuery](https://jquery.com/)
* Mustach (4.0.1) [Mustach](https://mustache.github.io/)
* GSAP (v3.5.1) [GSAP](https://greensock.com/gsap/)
* pdfjs-dist via [pdfjs-dist](https://www.npmjs.com/package/pdfjs-dist)

### Prerequisites

1. Good code editor - Recommended: [VSCode](https://code.visualstudio.com/) settings are preconfigured
2. Supported web browser (Chrome, Edge, Firefox, ...)
3. [Node.js LTS](https://nodejs.org/en/) (> 14.x with npm >7) installed
4. Familiarity with the command line

### Install Node.js

First, check if you already have node and npm installed. To check if you have Node.js installed, run this command in your terminal:

```
node -v
```

If node is not installed on your machine, you can go to the official [nodejs.org](http://nodejs.org/) website, and choose the version depending on your operating system:

[Install Node.js and npm on Windows, Linux or Mac OSX](https://nodejs.org/en/download/)

### Check the npm version

npm is a separate project from Node.js, and tends to update more frequently. As a result, even if you’ve just downloaded Node.js (and therefore npm), you’ll probably need to update your npm. To confirm that you have npm installed you can run this command in your terminal:

```
npm -v
```

Luckily, npm knows how to update itself! To update your npm, type this into your terminal:

```
npm install --global npm@latest
```