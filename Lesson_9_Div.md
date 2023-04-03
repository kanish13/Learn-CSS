HTML Div:

•	The div tag defines a division or a section in an HTML document.
  
•	The div tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript.
  
•	The div tag is easily styled by using the class or id attribute.
  
Example:
  
Index.html
  
    <div>
        <h1>Im Kanish</h1>
        <p>Programmer</p>
    </div>

Style.css
  
    div{
  
        background-color: #C8FFD4;

    }
  
Output:
 
![image](https://user-images.githubusercontent.com/111358462/229568258-dfca6eb5-0de0-421f-a4e3-732f006c5c94.png)


•	As you can see in the above example , div is not completely covering the top ,left or right area near that. 
  
•	This is because of default styling in the web browser
  
•	To manipulate it:

Style.css:

    body{
        margin: 0px;
    }
    h1{
        margin: 0px;
    }

Output:
  
![image](https://user-images.githubusercontent.com/111358462/229568328-1675f981-fbef-4357-8b3b-fe790b044802.png)

