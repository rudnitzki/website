Demo hosted on GitHub (GitHub Pages):
https://boilerplate.saeidmohadjer.com/

## A boilerplate for building modern HTML Websites

### You can use this boilerplate to build static responsive HTML sites that can be run on any server. 

**Features**
* Uses npm scripts without task runners such as Gulp or Grunt to do a variety of tasks such as support for Sass, transpiling ES6, and minifying CSS and scripts.
* No dependency on CSS or JavaScript frameworks
* Full support of ES6 features including ES6 modules
* Support and precompiling of Handlebars templates
* Automated deployment of built version to GitHub Pages using GitHub Actions after every commit to master

**Requirements**
* Local server capable of serving HTML files
* Latest version of Nodejs and NPM

**Usage**
* Clone repo and run "npm install" from command line.
* Run: "npm start" to serve files from "public" folder on local server
* Run: "npm run build" to build project into the "dist" folder

**Hosting Website on GitHub**

To host your Website on GitHub Pages you need a GitHub account. If you don't have one, you can create an account at: https://github.com/signup

Once you have created and logged into your account you need to create a public repository for your site there. Go to https://github.com/new and for repository name enter website or whatever you like (use a single lowercase word) and then click the green button to create the repository. 

Next you need to push your site to this repository and setup GitHub Pages and GitHub Actions to automate building and delploying of your site after every change. If you don't feel comfortable doing such changes yourself you can invite me as a collaborate to your repository so I will do them. To do this go to Settings tab of your repository and in sidebar select “Manage access”. Then click on “Add people” button and search for username "smohadjer" to invite me as a collaborator.

