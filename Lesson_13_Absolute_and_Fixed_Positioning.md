CSS Absolute Positioning:

The absolute positioning is used to position an element relative to the first parent element that has a position other than static. If no such element is found, the containing block is HTML.

Ex:

    h2 {  
        position: absolute;  
        left: 150px;  
        top: 250px;  
    }  

CSS Fixed Positioning:

The fixed positioning property helps to put the text fixed on the browser. This fixed test is positioned relative to the browser window, and doesn't move even you scroll the window.

Ex:

    p.pos_fixed {  
        position: fixed;  
        top: 50px;  
        right: 5px;  
        color: blue;  
    }  

CHALLENGE 1:

Achieve the below output:

![image](https://user-images.githubusercontent.com/111358462/229998805-48dda9dc-e11f-43c6-a1bc-12004b904b55.png)


Program:

HTML:

    <body>
    <div class="red"></div>
    <div class="blue"></div>
    <div class="yellow"></div>
    </body>

CSS:

    body{
      margin:0px;
    }
    .red{

      width: 100px;
      height: 100px;
      background: red;
      position:absolute;
      left:200px;
      top:200px;

    }
    .blue{

      width: 100px;
      height: 100px;
      background: blue;
      position:absolute;
      left:100px;
      top:100px;
    }
    .yellow{

      width: 100px;
      height: 100px;
      background: yellow;
      position:absolute;  
    }

CHALLENGE 2:

Achieve the below output:

![image](https://user-images.githubusercontent.com/111358462/229998895-01caa945-ed42-4145-af97-e35522e57b1f.png)


Program:

HTML:

    <body>
    <div class="container">
    <div class="red"> 
    </div>
    </div>
    <div class="blue"></div>
    <div class="yellow"></div>
    </body>

CSS:

    body{
      margin:0px;
    }
    .container{
      position:relative;
      height:300px;
      width:300px;
      background:grey;
    }
    .red{

      width: 100px;
      height: 100px;
      background: red;
      position:absolute;
      right:0;  
    }
    .blue{

      width: 100px;
      height: 100px;
      background: blue;
      position:absolute;
      top:0px;
      left:100px;       
    }
    .yellow{ 
      width: 100px;
      height: 100px;
      background: yellow;
      position:absolute;
      top:0px;  
    }
