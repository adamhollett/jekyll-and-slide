# Jekyll and Slide

Jekyll and Slide is a skeleton [Jekyll](http://jekyllrb.com) site that embeds hakimel's [reveal.js](//github.com/hakimel/reveal.js) framework for creating slideshows, letting you quickly write slideshows with Markdown. The site theme is [Lanyon](//github.com/poole/lanyon) by [mdo](//github.com/mdo).

## Contents

-   [Usage](#usage)
-   [Options](#options)
    -   [Slide separators](#slide-separators)
    -   [Title slide](#title-slide)
    -   [Themes](#themes)
-   [Development](#development)
-   [Author](#author)
-   [License](#license)

## Usage

Create a site by cloning or downloading this repository. Navigate to the directory where you copied it and run `jekyll serve` to view the site in your browser at `localhost:4000`. Press `ctrl` + `C` in your terminal to stop the server.

Create new slideshows by writing `.md` files in the `_slides` directory. Use [slide separators](#slide-separators) in your Markdown to create individual slides. `index.html` lists all the slideshows in the `_slides` directory.

If you want to use more complicated reveal.js features like fragments, you can just switch to HTML.

## Options

You can customize Jekyll and Slide in a few ways:

### Slide separators

You can define what characters to use as slide separators in `_config.yml`. By default these are:

```yaml
reveal:
  slide_separator:    "<hr />"
  vertical_separator: "<p>~~</p>"
  notes_separator:    "<p>Notes:</p>"
```

Slide separators are evaluated **after** the slide Markdown is rendered into HTML. So you can write `----` and `~~` for separators in your Markdown files, but Jekyll interprets them as `<hr />` and `<p>~~</p>`.

### Title slide

```yaml
reveal:
  title_slide: true
```

Slideshows will begin with a slide that shows the title, URL, and description defined in the file's front matter.

### Themes

You can optionally specify a theme for slide decks in the front matter of a `.md` file:

```yaml
---
theme: sky
---
```

The reveal.js readme lists the [available themes](//github.com/hakimel/reveal.js#theming). You can also make your own.

## Author

**Adam Hollett**

-   <https://github.com/admhlt>
-   <https://twitter.com/admhlt>

## License

Open sourced under the [MIT license](LICENSE.md).

## Credit

Thanks to [hakimel](//github.com/hakimel), [mdo](//github.com/mdo), and [ngoldman](//github.com/ngoldman) for the stuff that this is built on. I really didn't do much.
