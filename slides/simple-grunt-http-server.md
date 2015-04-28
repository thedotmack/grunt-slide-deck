##  Simple grunt http server

    $ npm install grunt-contrib-watch --save-dev
    $ npm install grunt-contrib-connect --save-dev
    $ echo 'Hello World!' > index.html

In `Gruntfile.js`, edit the `grunt.initConfig()` function and add the following:

    grunt.initConfig({
        connect: {
            server: {
                options: {
                    open: true,
                    livereload: true
                }
            }
        },
        watch: {  
        }
    });

note:
    - Now let's set up some Grunt tasks that create a simple http server, and will listen for file changes while we work so we can set our browser to Livereload when we save files in our project.
