CSS FONT:

Generic Font Families

In CSS there are five generic font families:

1.	Serif fonts have a small stroke at the edges of each letter. They create a sense of formality and elegance.
2.	Sans-serif fonts have clean lines (no small strokes attached). They create a modern and minimalistic look.
3.	Monospace fonts - here all the letters have the same fixed width. They create a mechanical look. 
4.	Cursive fonts imitate human handwriting.
5.	Fantasy fonts are decorative/playful fonts.
6.	Difference Between Serif and Sans-serif Fonts
 
Generic Font Family	Examples of Font Names

![image](https://user-images.githubusercontent.com/111358462/230308212-b9172fe4-940b-4c25-ae9e-1f8dba7b988d.png)


CSS WEB SAFE FONT:

Web safe fonts are fonts that are universally installed across all browsers and devices.

However, there are no 100% completely web safe fonts. There is always a chance that a font is not found or is not installed properly.
Therefore, it is very important to always use fallback fonts.
This means that you should add a list of similar "backup fonts" in the font-family property. If the first font does not work, the browser will try the next one, and the next one, and so on. Always end the list with a generic font family name.
Example
Here, there are three font types: Tahoma, Verdana, and sans-serif. The second and third fonts are backups, in case the first one is not found.

    p {
    font-family: Tahoma, Verdana, sans-serif;
    }

You can get variety of fonts in https://fonts.google.com/

Example :

If you are using Merienda, Monserrat, sacramento fonts for your webpage you need to add following links inside your head tag:

HTML:

    <head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Merienda&family=Montserrat&family=Sacramento&display=swap" rel="stylesheet">
    <head>

CSS:

    body{  
        font-family: 'Merienda', cursive;
    }
    h1{   
        font-family: 'Sacramento',cursive;
    }


OUTPUT:

![image](https://user-images.githubusercontent.com/111358462/230308826-3303289f-6b44-4637-971d-f707eb417ff6.png)

 
