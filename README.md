blog

Hugo site using the [hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme (vendored in `themes/`).

## Adding a page

New blog post:

    hugo new blog/my-post-title.md

New page in another section (e.g. reading log):

    hugo new reading/2027_reading.md

Edit the generated file, set `draft: false` when ready to publish. Preview locally with `hugo server -D`, build with `hugo`.

