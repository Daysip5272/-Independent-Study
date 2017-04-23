# Functions and operations
### Arithmetic and color
Sass comes with functions thats it easier to working
with colors.

There is something called alpha parameter in a color like RGBA or HSLA. The alpha parameter, 
specifies how one color should be merged with another when the two are on top of each 
other.

In Sass there is a function that is fade-out that makes a color more transparent by taking a 
number between 0 and 1 and decreasing opacity.
  ```scss
  $color: rgba(39, 39, 39, 0.5);
   $amount: 0.1;
   $color2: fade-out($color, $amount);//rgba(39, 39, 39, 0.4)
   ```
Also their another function that is the fade-in color function that changes a color by increasing its opacity:

```scss
$color: rgba(55,7,56, 0.5);
$amount: 0.1;
$color2: fade-in($color, $amount); //rgba(55,7,56, 0.6)
```
### Color Functions
As for Sass, it has many other
functions that can be combined with mathematical functions to
compute measurements—including colors.

Those kind of functions are called computes colors and this is how it works:

The operation is performed on the following components.
It computes the answer by operating on every two digits.
```scss
$color: #010203 + #040506;
```
The above would compute piece-wise as follows:
```scss
01 + 04 = 05
02 + 05 = 07
03 + 06 = 09
```
and compile to:
```scss
color: #050709;
```
Sass arithmetic can also compute HSLA and string colors such as red and blue.

For example:
```scss
color: red + blue;
```
will compile to:
```scss
color: magenta;
```
### Arithmetic
Sass has multiple arithmetic operations that are:

* addition ```+```
* subtraction ```-```
* multiplication ```*```
* division ```/```, and
* modulo ```%```

Note: Modulo, or %, is the remainder in a given division, so "9%2" would be "1".

## Takeaways 
1. Learn the basic first before making something complicated. Once you know to work the basic and get it working the right way, the rest will be kind easy since you already know that the lines that you just wrote, there may be something wrong. Don't rush, be patient! 
2. The best way to learn SASS is to create a simple table on your terminal. I had started by only reading everything and it was confusing because it had confusing parts that i really did not understand and could not picture it on my head. So, to understand every little part of the code I play around with the code to see what each parts does. 