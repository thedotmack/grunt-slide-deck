##  Using Jade Templates with JSON data (Cont'd)

    jade: {
        dist: {
            options: {
                data: function() {
                    return {
                        blog_posts: require( __dirname + '/assets/data/blog-posts.json')
                    }
                }
            },
            files: {
                "index.html": "assets/templates/index.jade",
                "blog-post.html": "assets/templates/blog-post.jade"
            }
        }
    },

