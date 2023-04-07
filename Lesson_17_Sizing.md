CSS FONT SIZE:

Here we are discussing about font sizing but sizing are common to all the css properties where you can modify the size.

Font Size:

The font-size property sets the size of the text.

Set Font Size With Pixels:

Setting the text size with pixels gives you full control over the text size:

Ex:

    h1 {
      font-size: 40px;
    }

Set Font Size With Percentage:

This is useful when the users visit your website in different gadgets (pc/tablet/mobile) and it should look same everywhere.

Ex:

    Hh{
     font-size:100%;
    }

Set Font Size With Em:

To allow users to resize the text (in the browser menu), many developers use em instead of pixels.
1em is equal to the current font size. The default text size in browsers is 16px. So, the default size of 1em is 16px.
The size can be calculated from pixels to em using this formula: pixels/16=em

Ex:

    h1 {
      font-size: 2.5em; /* 40px/16=2.5em */
    }

Set Font Size With Rem:

This is useful when you have some other font-size in parent tag/class/id and it should not affect the child class/id ,we use rem.

Ex:

    H1{
      font-size:5rem;
    }




