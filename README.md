# Irish Garden Birds

A website dedicated to educating people all about the birds and wildlife found in Irish gardens. This website was created as part of a web dev assignment for WIT's Computer Science HDip course. It can be found [here](https://irish-garden-birds.netlify.app/).

## Technologies Used

This site has been built with [Eleventy](https://www.11ty.dev/), a simple static site generator, using the [Nunjucks](https://mozilla.github.io/nunjucks/templating.html) templating language. The website has been deployed on [Netlify](https://app.netlify.com/).

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- Eleventy
	- ```npm install -g @11ty/eleventy```
- Eleventy Navigation
	- ```npm install @11ty/eleventy-navigation --save-dev```

### Project Setup

- In a command prompt/shell, navigate to the project directory and run ```eleventy```. This will build the site in the **_site** directory.
- Run ```eleventy --serve``` to serve the site locally with hot-reloading.

## Project Structure

### Layouts and Partials

All layouts and partials are contained in the **_includes** folder. .njk files use layouts by setting ```layout``` to the layout name, either as a variable in the front matter, or as a key/value pair in a JSON file in the containing folder. Partials are included in other .njk files using Nunjucks include statements: ```{% include "partial-name.njk" %}```

### CSS

**main.css** contains all global styles and imports other .css files, most of which come from the **/css/partials** directory. The **/css/pages** directory contains page-specific stylesheets.

### Collections

All news articles are found in the **/news** folder. Similarly, all birds & wildlife items are found in **/birds-&-wildlife**

## Sources

Much of the text, images and audio on this website has been adapted from content found on the following sites:
- [https://www.british-birdsongs.uk/](https://www.british-birdsongs.uk/)
- [https://www.rspb.org.uk/](https://www.rspb.org.uk/)
- [https://birdwatchireland.ie/](https://birdwatchireland.ie/)
- [http://clipart-library.com/clipart/rijrB5j8T.htm](http://clipart-library.com/clipart/rijrB5j8T.htm)
- [https://afunnyanimal.blogspot.com/2011/09/english-garden-birds-pictures.html](https://afunnyanimal.blogspot.com/2011/09/english-garden-birds-pictures.html)
- [https://www.hertswildlifetrust.org.uk/blog/wild-home/easter-garden-birds-and-their-nests-eggs](https://www.hertswildlifetrust.org.uk/blog/wild-home/easter-garden-birds-and-their-nests-eggs)
- [https://voice.gardenbird.co.uk/what-happens-after-the-fledgling-period/](https://voice.gardenbird.co.uk/what-happens-after-the-fledgling-period/)
- [https://codepen.io/patrykjachowski/pen/jvQBxG](https://codepen.io/patrykjachowski/pen/jvQBxG)
