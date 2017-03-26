# Entry 1: Intro / Plan
I had spent the past week going through sites searching for an specific topic to start learning about
through this 9 weeks. Since I like CSS I decided to do an independent study about SASS. Which is another 
similar to CSS. For that reason I started to begin working on codecademy where it just giving me 
review on how SASS works. Working on codecademy had help me reviewed and
expanded on my knowledge on stuff that I had forgotten about HTML/CSS. Through this process I had learn
and review a lot of stuff but as I go i'm still learning on how SASS works and for me it had made me get really interested in it.
As where I am right now, i'm still reviewing and learning more about SASS. 

## What is Sass?
SASS is a css preprocessor which is a scripting language that extends CSS by allowing developers
to write code in one language and then compile it into CSS. Sass stand for Syntactically Awesome StyleSheets which  is an extension of CSS. 
Sass allows you to use things like variables, nested rules, inline imports and more. 
It can also help you to keep things organized and also it allows you to create stylesheets faster.
## Learning about SASS
As I begging learn SASS I learn that it includes two syntax. The first one is SCSS (Sassy CSS) 
which uses .scss file and is fully compliant with CSS syntax. The other one is indented which is .sass file and uses indentation rather than brackets.
Also SASS allows the use of variables which can store information you can use throughout your stylesheet.
For example, you can store a color or size value in a variable at the top of the file, and then use this variable when setting the color or size of
your elements. With that it can allows you to quickly change your colors without having to modify each line.

For instance,
```ruby
@import url(https://fonts.googleapis.com/css?family=Pacifico);
//Add variables here:
$translucent-white: rgba(255,255,255,0.3);
$icon-square-length: 300px;
$standard-border: 4px solid black;
h1 {
  font-family: Roboto, sans-serif;
  text-align: center;
}

.banner {
  font-family: 'Pacifico', cursive;
  height: 400px;
  background-image: url("lemonade.jpg");
  border : {
    top: $standard-border;
    bottom: $standard-border;
}
}
.slogan {
  position: absolute;
  border: $standard-border;
  top: 200px;
  left: 25%;
  width: 50%;
  height: 200px;
  text-align: center;
  background-color: $translucent-white;
}
span {
  font-size: 24px;
  line-height: 200px;
}

.container {
  text-align: center;
  font-family: 'Pacifico', cursive;
}
.icon {
  display: inline-block;
  margin: 2%;
  border: $standard-border;
  font-size: 32px;
  width: $icon-square-length;
height: $icon-square-length;
}
```
The following CSS will be produced:
```ruby
@import url(https://fonts.googleapis.com/css?family=Pacifico);
h1 {
  font-family: Roboto, sans-serif;
  text-align: center;
}

.banner {
  font-family: 'Pacifico', cursive;
  height: 400px;
  background-image: url("lemonade.jpg");
  border-top: 4px solid black;
  border-bottom: 4px solid black;
}

.slogan {
  position: absolute;
  border: 4px solid black;
  top: 200px;
  left: 25%;
  width: 50%;
  height: 200px;
  text-align: center;
  background-color: rgba(255, 255, 255, 0.3);
}

span {
  font-size: 24px;
  line-height: 200px;
}

.container {
  text-align: center;
  font-family: 'Pacifico', cursive;
}

.icon {
  display: inline-block;
  margin: 2%;
  border: 4px solid black;
  font-size: 32px;
  width: 300px;
  height: 300px;
}
```
Mainly this is how SASS works but im still learning more as I go.

## Takeaways

Let's reflect for a moment:

1. What I had learn is that, as we research on our new topic we learn better when we try it. 
The better way to learn comer from doing it. At the beginning is hard to decide on what to do but
by trying and doing a topic you are interesting in makes it easier to learn.
2. When it comes time to choice, choice on something that interested and inspired you. Base on things you enjoy doing. 
3. If something interest you just review the basic things about it; will make it easier to keep learning about it.