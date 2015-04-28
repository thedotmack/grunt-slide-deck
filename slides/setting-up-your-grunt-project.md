##  Setting up your Grunt project

Make sure you have `npm` set up, the Node.js package manager. Create a new project folder and type the following:

    $ echo "{}" > package.json
    $ npm install -g grunt --save-dev
    $ touch Gruntfile.js

Open up `Gruntfile.js` and write:

    module.exports = function(grunt) {
        // Project configuration.
        grunt.initConfig({
        });
    };

note:
    What we're doing here, is creating 2 files, a package.json and a Gruntfile.js. 
    The package is going to contain all of the plugins we're going to install 
    Packages get automatically added when we flag them with --save or --save-dev
    The Gruntfile.js is your set of automation instructions
