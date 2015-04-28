##  Simple grunt http server (Con't)

Now, towards the bottom of `Gruntfile.js` <br>but before the closing `};` add:

    // These plugins provide necessary tasks.
    grunt.loadNpmTasks('grunt-contrib-watch');
    grunt.loadNpmTasks('grunt-contrib-connect');
        
    grunt.registerTask('serve', ['connect','watch']);
    
    // Default Task
    grunt.registerTask('default', 'serve');

You can now type `grunt` in your terminal, and a browser window will pop up and go to the url `http://0.0.0.0:8000`. 

<small>*The server only runs as long as grunt is running, therefore we run the `watch` task <br>to not only watch for file changes, but also to keep the server alive.*</small>

note:
    Now let's set up some Grunt tasks that create a simple http server, and will listen for file changes while we work so we can set our browser to Livereload when we save files in our project.

    You can see them pressing 's'.
