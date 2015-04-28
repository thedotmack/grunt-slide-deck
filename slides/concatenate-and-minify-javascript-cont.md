##  Concatenate and Minify Javascript (Cont'd)

In the `grunt.initConfig` function, in between the last line of the `connect` configuration, and the first line of the `watch` configuration:

    uglify: {
        js: {
            files: {
                'assets/js/main.min.js': 'assets/js/main.js'
            }
        }
    },

*Warning: Be aware of your commas!*

note:
    - Now let's configure our settings. 
    - Be aware of your commas! Make sure all properties at all levels of the configuration tree are seperated by `,` and make sure the last property at that level of the tree doesn't have a trailing comma. If you mess up your commas, you're going to have a bad time.