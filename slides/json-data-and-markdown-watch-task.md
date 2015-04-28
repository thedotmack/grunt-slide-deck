##  JSON Data &amp; Markdown Watch Task

    data: {
        files: [ 
            'assets/templates/**/*.jade', 
            'assets/data/**/*.json', 
            'assets/data/**/*.md' 
        ],
        tasks: [ 'jade', 'markdown' ],
        options: {
            livereload: true,
        }               
    }
