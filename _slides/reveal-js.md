---
title: reveal.js
description: The HTML presentation framework
theme: black
---

## Hello there

reveal.js enables you to create beautiful interactive slide decks using HTML. This presentation will show you examples of what it can do.

----

## Vertical slides

Slides can be nested inside of each other.

Use the **Space** key to navigate through all slides.

<a href="#" class="navigate-down">
  <img width="178" height="238" data-src="https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png" alt="Down arrow">
</a>

~~

## Basement level 1

Nested slides are useful for adding additional detail underneath a high level horizontal slide.

~~

## Basement level 2

That's it, time to go back up.

<a href="#/2">
  <img width="178" height="238" data-src="https://s3.amazonaws.com/hakim-static/reveal-js/arrow.png" alt="Up arrow" style="transform: rotate(180deg); -webkit-transform: rotate(180deg);">
</a>

----

## Slides

Not a coder? Not a problem. There's a fully-featured visual editor for authoring these, try it out at [slides.com](http://slides.com).

----

## Point of view

Hold down **alt** and click on any element to zoom in on it using [zoom.js](http://lab.hakim.se/zoom-js). **alt** + **click** anywhere to zoom back out.

----

## Touch optimized

Presentations look great on touch devices, like mobile phones and tablets. Simply swipe through your slides.

----

## Markdown support

Write content using pure Markdown.

Instructions and more info available in the [readme](https://github.com/admhlt/jekyll-and-slide).

```html
  ## Markdown support

  Write content using pure Markdown.

  Instructions and more info available in the [readme](https://github.com/admhlt/jekyll-and-slide).
```

----

## Fragments

Hit the next arrow...

<span class="fragment">... to step through ...</span>

<span class="fragment">... a</span> <span class="fragment">fragmented</span> <span class="fragment">slide.</span>

~~

## Fragment Styles

There's different types of fragments, like:

<p class="fragment grow">grow</p>

<p class="fragment shrink">shrink</p>

<p class="fragment fade-out">fade-out</p>

<p class="fragment current-visible">current-visible</p>

<p class="fragment highlight-red">highlight-red</p>

<p class="fragment highlight-blue">highlight-blue</p>

----

## Transition styles

You can select from different transitions, like:

-   [None](?transition=none#/7)
-   [Fade](?transition=fade#/7)
-   [Slide](?transition=slide#/7)
-   [Convex](?transition=convex#/7)
-   [Concave](?transition=concave#/7)
-   [Zoom](?transition=zoom#/7)

----

## Pretty code

```js
function linkify( selector ) {
  if( supports3DTransforms ) {

    var nodes = document.querySelectorAll( selector );

    for( var i = 0, len = nodes.length; i &lt; len; i++ ) {
      var node = nodes[i];

      if( !node.className ) {
        node.className += ' roll';
      }
    }
  }
}
```

Code syntax highlighting courtesy of [Rouge](http://rouge.jneen.net).

----

## Marvelous lists

-   No order here
-   Or here
-   Or here
-   Or here

----

## Fantastic ordered lists

1.  One is smaller than...
2.  Two is smaller than...
3.  Three!

----

## Tabular tables

| Item     | Value | Quantity |
|-----------------------------|
| Apples   |    $1 |        7 |
| Lemonade |    $2 |       18 |
| Bread    |    $3 |        2 |

----

## Clever quotes

These guys come in two forms, inline: <q cite="http://searchservervirtualization.techtarget.com/definition/Our-Favorite-Technology-Quotations">&ldquo;The nice thing about standards is that there are so many to choose from&rdquo;</q> and block:

> &ldquo;For years there has been a theory that millions of monkeys typing at random on millions of typewriters would reproduce the entire works of Shakespeare. The Internet has proven this theory to be untrue.&rdquo;

----

## Intergalactic interconnections

You can link between slides internally, [like this](#/2/3).

----

## Speaker view

There's a [speaker view](https://github.com/hakimel/reveal.js#speaker-notes). It includes a timer, preview of the upcoming slide as well as your speaker notes.

Press the **S** key to try it out.

Notes:

Oh hey, these are some notes. They'll be hidden in your presentation, but you can see them if you open the speaker notes window (hit S on your keyboard).

----

## Take a moment

Press **B** or **.** on your keyboard to pause the presentation. This is helpful when you're on stage and want to take distracting slides off the screen.
