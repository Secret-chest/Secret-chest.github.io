# Secret-chest.github.io
My website. Written in only plain HTML and CSS, though I might add a Jekyll blog.

## Use as a template
This site's role doubles itself as a template. You can fork it right now and replace my projects with yours.
It features a material asthetic. There are some components, including cards (`.card-full`), custom link buttons (`.button`, and you can make even a normal button look like it). The home page is simple and just features vertical content, while the projects page contains a flexbox (`.cards`) which contains cards. The cards in the flexbox can be made larger with the `.card-larger` class. Each project card has a background image with a gradient applied to it, but this is optional and is applied using inline styling (they are different after all). So this is a good starting point for a site, but it's my site too. LOL.

The site itself is very responsive. The content is always not wider than 576px, though it can become smaller if the viewport becomes smaller. One exception is the `.cards` article: it always is the width of the viewport, and the cards have `flex-grow` set to 1 so they make use of the available space efficiently. The buttons have a ripple effect to them, this makes them more satisfying to click. The effect is provided by [ripple-buttons](https://github.com/Secret-chest/ripple-buttons)
