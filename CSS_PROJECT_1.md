To achieve:

![image](https://user-images.githubusercontent.com/111358462/234929720-5e638298-fb1b-4d2c-84cf-62dd9710cdc9.png)

Solution Code:

index.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Spanish Vocabulary</title>
      <link rel="stylesheet" href="./style.css" />
    </head>

    <body>
      <h1>Colors</h1>
      <h2>Learn the colors in Spanish!</h2>
      <h2 class="color-title" id="red">Rojo</h2>
      <img class="color" src="./assets/images/red.png" alt="red" />

      <h2 class="color-title" id="blue">Azul</h2>
      <img src="./assets/images/blue.png" alt="blue" />

      <h2 class="color-title" id="orange">Anaranjado</h2>
      <img src="./assets/images/orange.png" alt="orange" />

      <h2 class="color-title" id="green">Verde</h2>
      <img src="./assets/images/green.png" alt="green" />

      <h2 class="color-title" id="yellow">Amarillo</h2>
      <img src="./assets/images/yellow.png" alt="yellow" />
    </body>

    </html>

    <!-- 
    TODOs
    IMPORTANT: You should not need to make ANY CHANGES to index.html
    All code should be written in your CSS file.

    1. Create a CSS file and incorporate it as an external stylesheet.
    2. Use CSS to style each of the color titles to meaning. 
    Hint: Use the id to help if you don't know the words in spanish.
    3. Use CSS to change all the color titles to have "font-weight: normal;"
    4. Use CSS (not HTML) to make all the images 200px heigh and 200px wide. 
    Hint: 
    https://developer.mozilla.org/en-US/docs/Web/CSS/height
    https://developer.mozilla.org/en-US/docs/Web/CSS/width
    -->

style.css:

    #red{
        color:red;
    }
    #blue{
        color: blue;
    }
    #orange{
    color: orange;
    }
    #green{
    color: green;
    }
    #yellow{
    color: yellow;
    }
    img{
        height: 200px;
        width: 200px;
    }
    h2[class=color-title]{
        font-weight: normal;
    }
