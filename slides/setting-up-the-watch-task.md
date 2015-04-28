##  Setting up the watch task

Add the following code inside your `watch` configuration:

    watch: {
        js: {
            files: [ 'assets/js/*.js' ],
            tasks: [ 'uglify:js' ],
            options: {
                livereload: true,
            }
        },
        css: {
            files: [ 'assets/less/*.less' ],
            tasks: [ 'less:style', 'autoprefixer:main' ],
            options: {
                livereload: true,
            }
        },
    }

<small>*In order for Livereload to work, you have to install the Livereload (http://livereload.com/) browser plugin.*</small>

note:
    Grunt's `watch` task allows you to listen for file changes, and then run tasks after those files change, as well as Livereloading your browser after those changes are made.


