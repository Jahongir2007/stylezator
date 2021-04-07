### Forms and inputs in stylezator
```htm
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
   <div class="box"> 
    <div class="form-box">
        <form action="/action_page.php">
          <label for="fname">First Name</label>
          <input class="form-input" type="text" id="fname" name="firstname" placeholder="Your name..">
      
          <label for="lname">Last Name</label>
          <input class="form-input" type="text" id="lname" name="lastname" placeholder="Your last name..">
      
          <label for="country">Country</label>
          <select id="country" name="country">
            <option value="australia">Australia</option>
            <option value="canada">Canada</option>
            <option value="usa">USA</option>
          </select>
          <input class="submit-input" type="submit" value="Submit">
        </form>
      </div>
      </div> 
  </body>
</html>
```
