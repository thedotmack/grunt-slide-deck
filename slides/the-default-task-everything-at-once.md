##  The Default Task, everything at once

    grunt.registerTask('serve', [
        'uglify:js',
        'less:style',
        'autoprefixer:main',
        'jade',
        'markdown',
        'connect',
        'watch'
    ]);
    
    // Default task.
    grunt.registerTask('default', 'serve');

