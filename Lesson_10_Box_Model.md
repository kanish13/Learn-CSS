BOX MODEL:

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:
 
 ![image](https://user-images.githubusercontent.com/111358462/229577819-1d0219f0-64e1-497e-bb3e-439b15307666.png)

 
Explanation of the different parts:

•	Content - The content of the box, where text and images appear

•	Padding - Clears an area around the content. The padding is transparent

•	Border - A border that goes around the padding and content

•	Margin - Clears an area outside the border. The margin is transparent

The box model allows us to add a border around elements, and to define space between elements. 

CHALLENGE:

Using padding, margin, border create a webpage like :

![image](https://user-images.githubusercontent.com/111358462/229577903-0c2d4030-d815-48be-8afd-d0e5f13e3516.png)

 
Index.html:

    <div class="top_container">
        <h1>Im Kanish</h1>
        <p>Programmer</p>
        </div>
        <div class="a">

        </div>
        <div class="b">

        </div>

Style.css:

    .top_container{
        background-color: #C8FFD4;
        height: 100px;
        width: 100px;
        border: solid 10px;
        padding: 20px;
    }
    .a{
        height: 100px;
        width: 100px;
        background-color: red;
        border: solid 20px;
        margin-left: 155px;


    }
    .b{
        height: 100px;
        width: 100px;
        background-color: blue;
        border: solid 10px;
        margin-left: 292px;
    }


