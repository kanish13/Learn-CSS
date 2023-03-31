Internal CSS:
Instead of using style inside the all tags, we can have separate style tag inside the head tag which is written only once to adapt for all tags

Change Background color:

      <head>
          <meta charset="UTF-8">

          <title>🧑‍💼 Kanish Personal Webite</title>
          <style>
              body {
                  background-color:rgb(96, 228, 162);
              }
          </style>
      </head>

 ![Screenshot (77)](https://user-images.githubusercontent.com/111358462/229183249-dd814821-91d5-4abb-8513-fd9bf99e2c37.png)


Horizontal Line Alteration:

      hr{
                background-color:white;
                border-style: none;
                height: 2px;
                width: 30%;
            }![Screenshot (79)](https://user-images.githubusercontent.com/111358462/229183511-dac647fb-4afe-43d1-b474-584b7316885f.png)

        
border-style: none; - THIS LINE REMOVES THE BORDER OF HORIZONTAL LINE

height: 2px; - THIS LINE DETERMINES HEIGHT OF LINE
width: 30%;  - THIS LINE DETERMINES WIDTH OF LINE
![Screenshot (78)](https://user-images.githubusercontent.com/111358462/229183409-be382c7e-f9b2-4149-80cc-916d46521b0d.png)

 

TASK:
TO DRAW DOTTED HORIZONTAL LINE OF WITH 10% AND COLOR GREY:

      hr{

                  border-style: none;
                  border-top-style: dotted;
                  border-color: grey;
                  border-width: 5px;
                  width: 5%;
              }


![Screenshot (79)](https://user-images.githubusercontent.com/111358462/229183603-e2dd1550-27db-48a0-ae4a-9704b99a2e53.png)


