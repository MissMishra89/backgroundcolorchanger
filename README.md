<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>randombgchanger</title>
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
      }
      body > div {
        height: 200px;
        width: 490px;
        border: 3px solid wheat;
        display: grid;
        grid-template-columns: auto auto auto;
        margin-top: 250px;
        border-radius: 20px;
        background-color: rgb(50, 49, 49);
      }
      body > div > button {
        background-color: grey;
        color: white;
        font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
        font-weight: bolder;
        font-size: 20px;
        width: 150px;
        height: 60px;
        border-radius: 20px;
      }
      /* body > div > button:hover {
        width: 170px;
        height: 80px;
        
        font-size: 25px;
      } */
    </style>
  </head>
  <body>
    <div>
      <button id="btn2" onclick="btn1('red')">RED</button>
      <button onclick="btn1('blue')">BLUE</button>
      <button onclick="btn1('green')">GREEN</button>
      <button onclick="btn1('yellow')">YELLOW</button>
      <button onclick="btn1('purple')">PURPLE</button>
      <button onclick="btn1('orange')">ORANGE</button>
      <button onclick="btn1('black')">BLACK</button>
      <button onclick="btn1('pink')">PINK</button>
      <button onclick="btn1('brown')">BROWN</button>
    </div>
  </body>
  <script>
    const btn1 = (color) => {
      document.body.style.backgroundColor = color;
    };
    if (document.getElementById("btn2").style.backgroundColor === "grey") {
      document.getElementById("btn2").style.backgroundColor = red;
    } else {
      document.getElementById("btn2").style.backgroundColor === grey;
    }
  </script>
</html>
# backgroundcolorchanger
