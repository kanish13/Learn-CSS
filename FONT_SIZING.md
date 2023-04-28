Font size:

Absolute:

As their name suggests, these units are of fixed size. They do not change according to screen size or anything else. After all, a centimeter is always a centimeter, right? These include

•	cm — centimeters

•	mm — millimeters

•	in — inches

•	pt — points

•	px — pixels

•	pc — pica

1 in = 2.54 cm = 254 mm = 72 pt = 96 px = 6 pc
 
![image](https://user-images.githubusercontent.com/111358462/235202696-5632ea01-90ad-4582-b8e4-6d6411b1df75.png)


Relative

This is where it gets a bit more complicated… In most browsers, the default font size is 16px — I suggest using this value as a basis for any relative calculations. Relative units are comprised of

•	% — percentage

•	em — font size of the element , relative to its parent(3em means that 3 times the normal font size)

•	rem — font size of the element, relative to the root html element

•	ch — width of the “0” character (in monospace fonts all characters are of equal width)

•	ex —x-height of the font used (the height of “x” character)

Font weight:

The font-weight property sets how thick or thin characters in text should be displayed.

Ex:

    p.normal {
      font-weight: normal;
    }

    p.thick {
      font-weight: bold;
    }

    p.thicker {
      font-weight: 900;
    }

o/p:

![image](https://user-images.githubusercontent.com/111358462/235202360-6465d73d-2d82-4a11-a1da-222d5d99c3c3.png)



