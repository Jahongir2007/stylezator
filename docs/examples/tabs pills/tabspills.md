### Tabs and pills in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <!--Tabs:-->
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'London')">London</button>
  <button class="tablinks" onclick="openTab(event, 'Paris')">Paris</button>
  <button class="tablinks" onclick="openTab(event, 'Tokyo')">Tokyo</button>
</div>

<div id="London" class="tabcontent">
  <h3>London</h3>
  <p>London is the capital city of England.</p>
</div>

<div id="Paris" class="tabcontent">
  <h3>Paris</h3>
  <p>Paris is the capital of France.</p> 
</div>

<div id="Tokyo" class="tabcontent">
  <h3>Tokyo</h3>
  <p>Tokyo is the capital of Japan.</p>
</div>
    <!--Pills:-->
    <button class="pillbtn">Pill Button 1</button>
    <button class="pillbtn">Pill Button 2</button>
  </body>
</html>
```
