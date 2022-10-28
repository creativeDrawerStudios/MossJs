<img src="sold.png" width="350" height="150"/>

> The <em>successor</em> to <a href="https://github.com/creativeDrawerStudios/eSharpBeta"><b>eSharp</b></a> <br/>
> Includes drawing, studio commands, and optional functions for repetetion.

``` js
 //This is a project made in moss.js
let screenX = screen.width;
let screenY = screen.height;
let centerX = screenX / 2;
let centerY = screenY / 2;
createCanvas(screenX,screenY);
bg("#00cfEE");
strokeSize(5);
strokeColor("#000000");
selectColor("#ff00cE");
rect(centerX-50,centerY-50,100,100);
```
## How to make a new project

### Start with a new html document

``` html
<!DOCTYPE html>
<html>
 <head>
  <title>myFirstMossProject</title>
 </head>
 <body>
  <p align="center">
   <canvas id="myCanvas"></canvas>
  </p>
  <script src="https://classicmc-studios.github.io/js/moss.js"></script>
  <script src="main.js"></script>
 </body>
</html>
```

#### Create a new js file called main.js

``` js
createCanvas(720,480);
bg("#00cc00",0.1);
strokeColor("#000000");
selectColor("#ffffff");
rect(720/2-50,480/2-50,100,100);
```

## Additions 

> <b>Studio</b>

``` js
const stdio = new Studio();
stdio.input("Hello World!");
```

> <b>Draw</b>

```js 
new Draw();
var draw = function(){
 //Runs once every millisecond
}
```
