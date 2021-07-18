# repository
<!DOCTYPE html>
<html>
  <head>
    <title>HTML Document</title>
<script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
    <style>
      body {
        background-color: linen;
      }
    </style>
  </head>
  <body>
    <h1>HTML Heading 1</h1>
    <p>HTML Paragraph</p> 
<div id="app-7">
  <ol>
    <todo-item
      v-for="item in TaskList"
      v-bind:todo="item"
      v-bind:key="item.id"
    ></todo-item>
  </ol>
</div>
    <p id="demo">Pre JavaScript</p>
    <button type="button" onclick='document.getElementById("demo").innerHTML = "Post JavaScript"'>Click Me</button>
    <p style="color:red">This is styled text</p>
    <img src="https://media.istockphoto.com/photos/colored-powder-explosion-on-black-background-picture-id1057506940?k=6&m=1057506940&s=612x612&w=0&h=C11yA-ESqeuCX63QkRpPyWmAMXJJvZw0niQluGnATlI=" alt="colors">
  </body>
</html>
 
