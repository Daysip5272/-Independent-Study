# Entry 2: Trying SASS
## How to install SASS
In order to install SASS into your workspace terminal check that you are in the right 
workspace and then in the terminal type `gem install sass`. 
And then type `sass -v`, it should return `Sass 3.4.23 (Selective Steve)`, if
it does not return that then SASS is not installed in your workspace terminal.
In case `gem install sass` does not work at all, then try `sudo gem install sass`.

Next, you should open a filed by typing in the terminal `touch input.scss` where a file would be created

After, add some sass code in `input.scss`, then in the terminal type `sass input.scss output.css`.

Once you did that, you should see a filename `output.css` where all of your changes from your SASS file would be.

After adding SASS code on SCSS file, go to the terminal and type  `sass input.scss output.css` to update it on the CSS file. 

Note: SCSS is another name for a SASS file

<img src="../images/Screen1.png"/><img src="../images/Screen2.png"/>

## Things that can be done on SASS
Unlike CSS, with SASS you can use variables. Those variables save certain elements properties
that can be use through many elements in differents parts of the code. To make a variable you add a dollar sign  `$` 
in front of the variable name.

For example:
``$color-mm:#00FFFF``

Another thing that can be done on scss is the following:
```
.parent {
  font : {
    family: Roboto, sans-serif;
    size: 12px;
    decoration: none;
  }
}
```
As a result for css is:
```
.parent {
  font-family: Roboto, sans-serif;
  font-size: 12px;
  font-decoration: none;
}
```
Through the second week I started to install SASS in cloud 9. Then
I learn the basic use of SASS. After learning, I beging to try it out.
## Takeaways
1. Don't give up and play around with the code and do not live anything blank.
Because there was this time that the sass code did not go to the css because I left something blank which made my entire 
css not work.
2. Double check that you are writing the variable name the right way so that element property could actually work.
3. Try to find examples of you topic and play around with it so that you can gain experiences and perspective on the
possibilities of what things can be done with it.




