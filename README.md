# General-knowledge-css
- tips for CSS

initiate html
<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="utf-8" />
-keep style between diferent devices 

<meta name="viewport" content="width=device-width, initial-scale=1.0" />

comments
/*----*/
</head>

.class-name {
  styles
}

body {
 background-image:url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
}

- html represent a individual info
 <article>
          </article>
          
        -  align a menu 
.flavor {
  text-align: left;
  width: 75%;
}

.price {
  text-align: right;
  width: 25%;
}

--padding for every side 

padding:20px

-- prevent element to be separated too much
max-width: 500px;

reduce spaces within image & title
 margin-top:-25px;
 
 name a class
 
  <div class="marker green">
      </div>
      
      giving style 
   .green {
  background-color: rgb(0, 0, 0) or #00ff00;
}


using HSL colors
 .blue {
  background-color: hsl(240, 100%, 50%); (color,saturation,lightness)
}

--exercise

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colored Markers</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <h1>CSS Color Markers</h1>
    <div class="container">
      <div class="marker red">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
      <div class="marker green">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
      <div class="marker blue">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
    </div>
  </body>
</html>



css exercise

h1 {
  text-align: center;
}

.container {
  background-color: rgb(255, 255, 255);
  padding: 10px 0;
}

.marker {
  width: 200px;
  height: 25px;
  margin: 10px auto;
}

.cap {
  width: 60px;
  height: 25px;
}

.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5);
  border-left: 10px double rgba(0, 0, 0, 0.75);
}

.cap, .sleeve {
  display: inline-block;
}

.red {
  background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
  box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
}

.green {
  background: linear-gradient(#55680D, #71F53E, #116C31);
  box-shadow: 0 0 20px 0 #3B7E20CC;
}

.blue {
  background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
  box-shadow: 0 0 20px 0 blue;
}
