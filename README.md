# `jamesprime.github.io`

Notes for myself (first-timer here; don't mind me):

## Default `leap-day` Important Theme Files

### HTML

`/_layouts/default.html` contains HTML giving the layout to be used, um, *by default*...  `/_layouts/home.html` is (presumably) the layout used for the static landing page, if specified; `/_layouts/page.html` is the layout used for pages; and of course `/_layouts/post.html` is the layout used for posts.  I know, who'd have thought, right?

Within these files, there will be `{{ liquid.tags }}`, which are used by Jekyll to input specific content into the given template files in `/_layouts/`.

### CSS

`/assets/css/style.scss` holds only the empty frontmatter and the single line `@import "{{ site.theme }}";`, which is basically a "call" to `/_sass/jekyll-theme-leap-day.scss`, which actually holds the style information.  So custom CSS should go under the `@import` line in `/assets/css/style.scss`, or in a separate file (that gets called in a tailored duplicate `@import` line in the same).

## Adding customised CSS and suchlike

Override Jekyll defaults with stuff in:

* `_layouts`
* `_includes`
* `_sass`
* `assets`
