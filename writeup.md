#Selectors, Properties, and Values
In this article I have included the CSS Selectors their Properties & Values given to the given properties. We can selector in class, type or identity. Here in the given example (p,div) ar type and (.box) is a class, class always starts with a dot with the class name. (#altcampus) is a identity selector, an identity selector always start with a #hashtag with the identity name.


#Selectors

##Type Selector:

###h1 {
  color: red;
  font-size: 34px;
}
p {
  background-color: green;
  color: red;
}
div {
  width: 400px;
  height: 300px;
}
##Class Selector:

###<div class="box">........</div>

.box {
  height: 150px;
  width: 150px;
  background-color: red;
}
##ID Selectors:

###  <div id="altcampus"></div>

  #altcampus {
    background-color: green;
  }


  #Referencing CSS
  You can take 3 different approach to connect your html with the css page.
  ##Inline Styling
Here you add you css element with the html type itslef in a single line code.
  ###<div style="background-color: red; color:blue; ">.......</div>

  ##Internal Styling:
Here you add your <style> to input the css requirement on the html page itself this will be hidden to the user interface.
  ####<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Hello World</title>
    <style>
      body {
        background-color: green;
      }
      .heading {
        color: black;
        font-size: 36px;
      }
    </style>
  </head>
  <body>
    <h1 class="heading">Hello World!</h1>
    <p>Our first web page.</p>
  </body>
</html>

##External Styling :
This is commonly used to avoid complexity where you add main.css page to your index.html file.

###<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>.......</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1 class="heading">Hello World!</h1>
    <p>Our first web page.</p>
  </body>
</html>