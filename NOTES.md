## PONG GAME 

### Intro
We gonna use a HTML and Javascript to make it.
We'll use a HTML 5 canvas.

create a html file and add a script tag, inside we put the game code.
open in your browser and inspect

### window. onload
use the function to run the game after all the page was charged
```js
//When the window finish the charges run the function
window.onload = function(){
    console.log("hello world")
}
```
### HTML <canvas>
Use in html section, inside will be all graphics 
```html
   <canvas id="gameCanvas" width="800" height="600">
   </canvas> 
```

### playing with canvas

the first argument fo fillRect is the left pos, second the top, third the right, four the bottom.
if a rectangle are over on others, the the last writing shows on top. Draw order is very important.

### Movement and Time

create a function to group all draw cod.
Using a variable to vary shape Draw Position.
Change the rectangle to circle like a ball.

### Pt8 Ball Reset and Collision



