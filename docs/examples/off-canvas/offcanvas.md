### Off-Canvas menu in Stylezator version 1.5.0
```markdown
     <!DOCTYPE html>
     <html>
      <head>
        <title>docs</title>
        <link rel="stylesheet" href="main/sty_css.css">
        <script src="main/sty_js.js"></script>
      </head>
      <body>
        <div id="mySidenav" class="sidenav-an">
          <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
          <a href="#">About</a>
          <a href="#">Services</a>
          <a href="#">Clients</a>
          <a href="#">Contact</a>
        </div>
        <span onclick="openNav()">open</span>

        <div id="main">
          ...
        </div>
      </body>
     </html>
```
