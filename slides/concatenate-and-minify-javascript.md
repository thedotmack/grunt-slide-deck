##  Concatenate and Minify Javascript

Type the following into your terminal at your project's root:

    $ npm install grunt-contrib-uglify --save-dev

Add the following to the bottom of your `Gruntfile.js` where you have your `grunt.loadNpmTasks` functions listed:

    grunt.loadNpmTasks('grunt-contrib-uglify');

note:
    You can use grunt to compress your JavaScript to serve smaller sized files to your users.
