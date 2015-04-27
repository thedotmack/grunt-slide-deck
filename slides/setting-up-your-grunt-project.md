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
    Put your speaker notes here.
    You can see them pressing 's'.
