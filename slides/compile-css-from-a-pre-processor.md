##  Compile CSS from a pre-processor

In your terminal in the project's root, type:

    $ npm install grunt-contrib-less --save-dev

Add the following to the bottom of your `Gruntfile.js` where you have your `grunt.loadNpmTasks` functions listed:

    $ grunt.loadNpmTasks('grunt-contrib-less');

note:
    Grunt is awesome for your workflow involving CSS preprocessors like LESS or SASS. The following is an example of how to set up your project to compile LESS files to CSS.
