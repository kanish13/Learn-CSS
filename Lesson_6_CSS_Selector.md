CSS Selectors:

•	Till now we have used only tag selectors . so disadvantage of this is , modification will be applied for all the tags of the same name .  For example if we apply modification for h1 . it will be adapted to all the h1 in the html page

•	So if we want to change only h1 tag, we have to use class selectors 

•	For this you have use class=”name-of-the-class” inside the tag

•	And go to css file and type:

.name-of-the-class{ modification }  

•	Do not forget the dot before the class name

For example:

Here I have created two different class for two different image

    <img class="baccon" src="https://em-content.zobj.net/thumbs/160/apple/81/bacon_1f953.png" alt="bacon-img">

    <img class="broccoli" src="https://em-content.zobj.net/thumbs/160/apple/325/broccoli_1f966.png" alt="broccoli-img">

 I have changed their bg color using their class names
 
    .baccon{
        background-color: aqua;

    }
    .broccoli{
        background-color: rgb(30, 255, 0);
    }


OUTPUT:

![image](https://user-images.githubusercontent.com/111358462/229327968-3d678d45-8eb1-488a-b618-bb1fcd734077.png)
