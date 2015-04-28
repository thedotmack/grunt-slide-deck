##  Autoprefixr (Cont'd)

Add this to the `grunt.initConfig` function, in between the last line of the `less` configuration, and the first line of the `watch` configuration:

    autoprefixer: {
        main: {
            src: 'assets/css/main.min.css',
        },
    },

note:
    Grunt is also real handy at keeping your code future forward, and gives you the freedom to code without having to remember vendor prefixes for new technologies.