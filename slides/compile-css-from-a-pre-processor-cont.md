##  Compile CSS from a pre-processor (Cont'd)

Add this to the `grunt.initConfig` function, in between the last line of the `uglify` configuration, and the first line of the `watch` configuration:

    less: {
        style: {
            files: {
                'assets/css/main.min.css': 'assets/less/main.less'
            }
        }
    },
