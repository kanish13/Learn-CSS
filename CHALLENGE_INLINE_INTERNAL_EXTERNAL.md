CHALLENGE:

Add the inline css , internal css , external css for the below file inline.html , internal.html , external.html and add the link of these files in index.html:
(Intruction are given in the h1 tag itself)

inline.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Inline</title>
    </head>

    <body>
    <h1>Style Me in Blue!</h1>
    </body>

    </html>

internal.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Internal</title>
    </head>

    <body>
    <h1>Style Me in Red!</h1>
    </body>

    </html>

external.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>External</title>
      <link rel="stylesheet" href="style.css">
    </head>
    <body>
      <h1>Style Me in Green</h1>
    </body>
    </html>
    

index.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Adding CSS</title>
    </head>

    <body>
      <h1>Three Methods of Adding CSS</h1>
      <!-- Create 3 Links to The 3 Webpages: inline, internal and external -->
      <a href=""></a>
    </body>

    </html>

Output Images:

![image](https://user-images.githubusercontent.com/111358462/234598016-6390510b-4e92-45e2-9299-b189446e01c4.png)

![image](https://user-images.githubusercontent.com/111358462/234598103-93065b74-e503-4ab7-aa86-3018073507a9.png)

![image](https://user-images.githubusercontent.com/111358462/234598166-87363161-215a-4861-881b-cc013d7c09b6.png)

![image](https://user-images.githubusercontent.com/111358462/234598243-6d6abe00-3497-4118-9767-cfc604bc1cd4.png)



Solution Code:

inline.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Inline</title>
    </head>

    <body>
      <h1 style="color: blue;">Style Me in Blue!</h1>
    </body>

    </html>

internal.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Internal</title>
      <style>
        h1 {
          color: red;
        }
      </style>
    </head>

    <body>
      <h1>Style Me in Red!</h1>
    </body>

    </html>

external.html: (For external css , you have to create the style.css file in the project directory and the following code)

    h1{
        color: green;
    }
  
index.html:

    <!DOCTYPE html>
    <html lang="en">

    <head>
      <meta charset="UTF-8">
      <title>Adding CSS</title>
    </head>

    <body>
      <h1>Three Methods of Adding CSS</h1>
      <!-- Create 3 Links to The 3 Webpages: inline, internal and external -->
      <a href="inline.html">Inline</a>
      <a href="internal.html">Internal</a>
      <a href="external.html">External</a>
    </body>

    </html>



