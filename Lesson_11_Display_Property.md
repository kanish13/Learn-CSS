Display Property:

Before actually moving into the display property in css . let us understand the block and inline elements in HTML

Block-level Elements:

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are: p and div.
  
The p element defines a paragraph in an HTML document.
 
The div element defines a division or a section in an HTML document.

The p element is a block-level element.

The div element is a block-level element.


Example

    <p>Hello World</p>
    <div>Hello World</div>

Here are the block-level elements in HTML:

    <address>
    <article>
    <aside>
    <blockquote>
    <canvas>
    <dd>
    <div>
    <dl>
    <dt>
    <fieldset>
    <figcaption>
    <figure>
    <footer>
    <form>
    <h1>-<h6>
    <header>
    <hr>
    <li>
    <main>
    <nav>
    <noscript>
    <ol>
    <p>
    <pre>
    <section>
    <table>
    <tfoot>
    <ul>
    <video>
    
Inline Elements:

An inline element does not start on a new line.

An inline element only takes up as much width as necessary.

This is a span element inside a paragraph.

Example

    <span>Hello World</span>

Here are the inline elements in HTML:

    <a>
    <abbr>
    <acronym>
    <b>
    <bdo>
    <big>
    <br>
    <button>
    <cite>
    <code>
    <dfn>
    <em>
    <i>
    <img>
    <input>
    <kbd>
    <label>
    <map>
    <object>
    <output>
    <q>
    <samp>
    <script>
    <select>
    <small>
    <span>
    <strong>
    <sub>
    <sup>
    <textarea>
    <time>
    <tt>
    <var>
    
Now let us see display property of css:

CSS display is the most important property of CSS which is used to control the layout of the element. It specifies how the element is displayed.

There are following CSS display values which are commonly used.

1.	display: inline;
2.	display: inline-block;
3.	display: block; 
4.	display: none;
 
 ![image](https://user-images.githubusercontent.com/111358462/229787898-6c47dc96-591a-4c47-8fad-9b6e6c317387.png)

display: none; is commonly used with JavaScript to hide and show elements without deleting and recreating them (doesn’t takes up the space)
 
The visibility property specifies whether or not an element is visible.

Ex:

    h2.b {
      visibility: hidden;
    }

(The element is hidden (but still takes up))
