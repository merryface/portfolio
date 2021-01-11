# Merryface Portfolio
![GitHub repo size](https://img.shields.io/github/repo-size/merryface/portfolio?logo=GitHub&style=for-the-badge)

## What is This Website?<br>
Welcome to the repo that contains the code for [my portfolio](https://merryface.github.io/portfolio/). It's a simple scrolling site which informs the user of my web development skill set, gives them examples of my work (hosted here on GitHub), and several ways to contact me.


## Gulp
`npm init -yes` was used in the command line to install npm. This created a `package.json` file, where the packages installed are listed. After that gulp was installed using `npm gulp install`.
The packages were installed by running `gulp install {package-name}` in the command line. This downloads the specific packages required.

### gulpfile.js
The `gulpfile.js` file contains all the methods used in order to:
- Turn all SCSS files into a single CSS file, for browser compatibility
- Concatinate all JS files into one
- Minify the CSS, and uglify the JS, for performance improvements
- Create a `watch` task that automatically runs these tasks when changes are applied to the developer files.

The final CSS and JS files which are linked into the final project have the `.min.{fileType}`.

### Replicating Workspace
To replicate the workspace, Run `git clone git@github.com:merryface/portfolio.git` followed by `npm install`. This should set up a local workspace.

## SCSS Layout
All SCSS files are stored in the scss file. All styling is done in scss and applied to each page using `style.min.css`.

