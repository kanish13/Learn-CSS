Static and Relative positioning:

position: static;

HTML elements are positioned static by default.

Static positioned elements are not affected by the top, bottom, left, and right properties.

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page

Example:

    div.static {
      position: static;
      border: 3px solid #73AD21;
    }

position: relative;

An element with position: relative; is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

Example:

    div.relative {
      position: relative;
      left: 30px;
      border: 3px solid #73AD21;
    }

CHALLENGE:

Write the css code to achieve the below output:

![image](https://user-images.githubusercontent.com/111358462/229815267-34df0e31-9a0c-4220-8a85-bdde37c50468.png)

 
Coding:

HTML:

    <div class="red"></div>
    <div class="blue"></div>
    <div class="yellow"></div>

CSS:

    .red{

      width: 100px;
      height: 100px;
      background: red;
      display:inline-block;
      position:relative;
      left:200px;
    }
    .blue{

      width: 100px;
      height: 100px;
      background: blue;
      display:inline-block;
      position:relative;
      right:100px;
    }
    .yellow{

      width: 100px;
      height: 100px;
      background: yellow;
      display:inline-block;
      position:relative;
      right:100px;


    }
