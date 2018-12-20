# hexhope
Hexo example for Existential Hope. See it [live](existentialhope.github.io).

## Getting Started
Most things that we would want to do can be done more easily using the Hexo CLI. For more information, check out the [documentation](https://hexo.io/docs/index.html). To get started:

    npm install -g hexo-cli

To add a new post:

    hexo new "A New Post"

This will create a new file in `source/_posts/` entitled `a-new-post.md`.

To deploy to GitHub Pages:

    hexo clean && hexo deploy --generate

## Development
Install dependencies:

    npm install

Run local server:

    hexo generate --watch

## Miscellaneous
The current theme is [Magnetic](https://github.com/klugjo/hexo-theme-magnetic).
The current Markdown renderer is Markdown-it via the [hexo-renderer-markdown-it](https://github.com/hexojs/hexo-renderer-markdown-it) plugin.
