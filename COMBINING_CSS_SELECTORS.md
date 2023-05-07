CSS Combinators

A combinator is something that explains the relationship between the selectors.

A CSS selector can contain more than one simple selector. Between the simple selectors, we can include a combinator.

There are four different combinators in CSS:

descendant selector (space)

child selector (>)

adjacent sibling selector (+)

general sibling selector (~)

Descendant Selector

The descendant selector matches all elements that are descendants of a specified element.

The following example selects all p elements inside div elements: 

Example

    div p {
      background-color: yellow;
    }
    
Child Selector (>)

The child selector selects all elements that are the children of a specified element.

The following example selects all p elements that are children of a div element:

Example

    div > p {
    background-color: yellow;
     }
     
Adjacent Sibling Selector (+)

The adjacent sibling selector is used to select an element that is directly after another specific element.

Sibling elements must have the same parent element, and "adjacent" means "immediately following".

The following example selects the first p element that are placed immediately after div elements:

Example

      div + p {
      background-color: yellow;
    }

General Sibling Selector (~)

The general sibling selector selects all elements that are next siblings of a specified element.

The following example selects all p elements that are next siblings of div elements: 

Example

      div ~ p {
      background-color: yellow;
    } 
    
EXERCISE:

TO ACHIEVE:

![jbjbk](https://user-images.githubusercontent.com/111358462/236690094-549599fe-29f3-4ac4-88c6-3c8d0f7eeace.png)

Index.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Combining CSS Selectors</title>
      <link rel="stylesheet" href="./style.css">
    </head>

    <!-- Don't change any of the HTML code! -->

    <body>
      <h1>To Do List</h1>
      <h2>Monday</h2>
      <div class="box">
        <p class="done">Do these things today!</p>
        <ul class="list">
          <li>Wash Clothes</li>
          <li class="done">Read</li>
          <li class="done">Maths Questions</li>
        </ul>
      </div>

      <ul>
        <p class="done">Other items</p>
      </ul>
      <p>The best preparation for tomorrow is doing your best today.</p>

    </body>

    </html>
    
NOW WRITE THE CSS CODE TO BRING THE APT OUTPU:

    /* Write your code here: */
    h1,h2{
        color: blueviolet;
    }
    .box > .done{
        color: firebrick;
    }
    .box li{
        color: blue;
    }
    li.done{
        color: seagreen;
    }
    ul p.done{
        font-size: 0.5rem;
    }
