##  Autoprefixr

In your terminal in the project's root, type:

    $ npm install grunt-autoprefixer --save-dev

Add the following to the bottom of your `Gruntfile.js` where you have your `grunt.loadNpmTasks` functions listed:

    $ grunt.loadNpmTasks('grunt-autoprefixer');

note:
    Grunt is also real handy at keeping your code future forward, and gives you the freedom to code without having to remember vendor prefixes for new technologies.