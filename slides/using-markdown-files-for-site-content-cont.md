##  Using Markdown Files for Site Content (Cont'd)

    markdown: {
        home: {
            files: {"index.html": "assets/data/content.md"},
            options: {template: 'index.html'}
        },
        blog: {
            files: [{
                expand: true,
                cwd: 'assets/data/blog-posts/',
                src: '*.md',
                dest: 'blog-posts/',
                ext: '.html'
            }],
            options: {template: 'blog-post.html'}
        }
    },

note:
    Put your speaker notes here.
    You can see them pressing 's'.
