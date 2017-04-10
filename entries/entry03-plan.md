# @Mixin & @include
Mixins can take multiple arguments.
Sass allows it to explicitly define each argument in your @include statement.
When values are explicitly specified you can send them out of order.

If a mixin definition has a combination of arguments with and without
a default value, you should define the ones with no default value first.

Here's an example of my input.scss below:
```scss
@mixin transform-style($style){
   transform-style: $style;
  -moz-transform-style: $style;
  -o-transform-style: $style;
  -ms-transform-style: $style;
  -webkit-transform-style: $style;
}
.notecard {
  @include transform-style(preserve-3d);
  width: 300px;
  height: 180px;
  border: 1px solid black;
  display: inline-block;}
```
Now, I'll show you the CSS code below:
```css 
.notecard {
  transform-style: preserve-3d;
  -moz-transform-style: preserve-3d;
  -o-transform-style: preserve-3d;
  -ms-transform-style: preserve-3d;
  -webkit-transform-style: preserve-3d;
  width: 300px;
  height: 180px;
  border: 1px solid black;
  display: inline-block;}
```
### Sass allows you to pass in multiple arguments in a list or a map format
When you include a mixin, then it can be pass in these arguments in a map with the following `...` notation.
```scss
$stripe-properties: to bottom, 15%, blue, white;

.definition {
    @include stripes($stripe-properties...);
      width: 100%;
      height: 100%;}
```
Now, I'll show you my CSS code below:
```css
.definition {
  background: repeating-linear-gradient(to bottom, white, white 14%, blue 1%, white 15%);
  width: 100%;
  height: 100%;
}
```
Also in Sass there is something called string interpolation which is the process of placing a
variable string in the middle of two other strings.
- it can be use when you want to make use of variables in selectors or file names

# Functions and operations
With Sass functions you can:

- Operate on color values
- Iterate on lists and maps
- Apply styles based on conditions
- Assign values that result from math 

## Takeaways 
1. Make sure you have a clear understanding of your own topic and how it can be used to create a project.
2. Learning to code takes time, but it’s worth it. Make sure to read everything because everything helps to learn and to better things with the stuff you had learn.
3. Break a part the code to learn what every like of does. 
4. Never give up and try it out, if you can`t solve it google it because he is your frined that will always help you out.