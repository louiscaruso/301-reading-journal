# Reading 12

## EJS Partials

- Handy when reusing same HTML across multiple views (nav bar, header, footer → stuff that stays static)
- Define reusable code in a file and include it wherever needed
- Any JS or non-html syntax is surrounded by `<% %>` delimiters
`<%- include( 'foldername/filename' ) %>`
- partial file is relative to the template you use it in
- partials are native to EJS
```
 <body>
        <div class="container">
            <%- include('partials/navbar') %>
            <div class="jumbotron">
                <h1>All about Node</h1>
                <p class="lead">Check out our articles below!</p>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="list-group">
                      <!-- loop over blog posts and render them -->
                      LIST_OF_POSTS
                    </div>
                </div>
            </div>
            <%- include('partials/footer') %>
        </div>
    </body>
```    