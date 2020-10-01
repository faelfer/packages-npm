# Introduction to the Managing Packages with npm Challenges
The Node Package Manager (npm) is a command-line tool used by developers to share and control modules (or packages) of JavaScript code written for use with Node.js.

When starting a new project, npm generates a `package.json file`. This file lists the package dependencies for your project. Since npm packages are regularly updated, the `package.json` file allows you to set specific version numbers for each dependency. This ensures that updates to a package don't break your project.

npm saves packages in a folder named `node_modules`. These packages can be installed in two ways:

1. globally in a root node_modules folder, accessible by all projects.
1. locally within a project's own node_modules folder, accessible only to that project.

Most developers prefer to install packages local to each project to create a separation between the dependencies of different projects. Working on these challenges will involve you writing your code on Repl.it on our starter project. After completing each challenge you can copy your public Repl.it URL (to the homepage of your app) into the challenge screen to test it! Optionally you may choose to write your project on another platform but it must be publicly visible for our testing.

Start this project on Repl.it using [this link](https://repl.it/badge/github/freeCodeCamp/boilerplate-npm) or clone [this repository](https://github.com/freeCodeCamp/boilerplate-npm/) on GitHub! If you use Repl.it, remember to save the link to your project somewhere safe!