## Stylezator  1.2.4
You can easily create a website through Stylezator ui framework. 
There are a lot of possibilities in this framework. Offical web page: https://jahongir2007.github.io/stylezator/
### Navbars in stylezator.
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="navbar">
      <li><a href="#logo" class="act">Stylezator.io</a>
      <li><a href="#docs">Docs</a>
      <li><a href="#themes">Themes</a>
      <li><a href="#plugins">Plugins</a>
      <li><a href="#examples">Examples</a>
    </div>
  </body>
</html>
```
### Typography in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="hd-jm">Stylezator framework
    <div class="hd-lt">This framework it's very simple and new UI framework</div>
    </div><br>
    <div class="hd-ht">
      UI frameworks
    </div>
    <div class="con">
      I love <mark>Stylezator</mark><br>
      <code>var x = 12;</code><br>
      <kbd>Enter</kbd><br>
      <pre>
        $(document).ready(function(){
          $(".test").onclick(function(){
            $(".test").hide();
          });
        });
      </pre>
    </div>
      <div style="width: 1000px;">
    <pre class="pre-scr">Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
    Delectus nesciunt reiciendis fuga deleniti rerum, vitae eligendi, perspiciatis repudiandae, odit distinctio cupiditate quod porro? 
    A nisi alias numquam assumenda officiis amet.s</pre>
    </div>
    <div class="t-w">Warning</div>
    <div class="t-sc">Succsess</div>
    <div class="t-m">Muted</div>
    <div class="t-pr">Primary</div>
    <div class="t-ip">Important</div><br>
    <div class="t-bg-w">Hello, world</div><br>
    <div class="t-bg-sc">Hello, world</div><br>
    <div class="t-bg-m">Hello, world</div><br>
    <div class="t-bg-pr">Hello, world</div><br>
    <p>Simple paragraph</p>
    <p class="ld">Stylezator paragraph</p>
    <p>Simple paragraph</p>
    <p>Simple paragraph</p>
    <p class="sml">Stylezator paragraph</p>
    <p>Simple paragraph</p>
    <p class="t-l">Lorem ipsum</p>
    <p class="t-cnt">Lorem ipsum</p>
    <p class="t-r">Lorem ipsum</p>
    <p class="t-nwp">Lorem ipsum</p>
    <p class="t-uns">Lorem ipsum</p>
    <p class="t-ini">Lorem ipsum</p>
    <p class="t-inh">Lorem ipsum</p>
    <p class="t-uc">Lorem ipsum</p>
    <p class="t-lc">Lorem ipsum</p>
    <p class="t-cl">Lorem ipsum</p>
    <ul class="li-grp">
      <li>Facebook
      <li>Instagram
      <li>Twitter
    </ul>
    <ol>
        <li class="li-no">Coffee
        <li class="li-sq">Juice
        <li class="li-lg">Water
        <li class="li-ll">Cat
    </ol>
    <ol>
        <li class="li-inl">Coffee
        <li class="li-inl">Juice
        <li class="li-inl">Water
        <li class="li-inl">Cat
    </ol>
    <dl>
        <dt class="dl-ho">Hello, world</dt>
        <dd class="dl-ho">Hello, world</dd>
    </dl>
  </body>
</html>
```
### Grid basic in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="col-pt-f" style="background-color:lavender;">.col-pt-f</div>
    <div class="col-pt-f" style="background-color:lavenderblush;">.col-pt-f</div>
    <div class="col-pt-f" style="background-color:lavender;">.col-pt-f</div>
  </body>
</html>
```
### Tables in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <table class="tl">
    <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr>
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Berglunds snabbköp</td>
        <td>Christina Berglund</td>
        <td>Sweden</td>
      </tr>
      <tr>
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr>
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
      <tr>
        <td>Island Trading</td>
        <td>Helen Bennett</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Königlich Essen</td>
        <td>Philip Cramer</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Laughing Bacchus Winecellars</td>
        <td>Yoshi Tannamuri</td>
        <td>Canada</td>
      </tr>
      <tr>
        <td>Magazzini Alimentari Riuniti</td>
        <td>Giovanni Rovelli</td>
        <td>Italy</td>
      </tr>
      <tr>
        <td>North/South</td>
        <td>Simon Crowther</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Paris spécialités</td>
        <td>Marie Bertrand</td>
        <td>France</td>
      </tr>
</table><br>
    <!--striped table:-->
    <table class="tl-spd">
    <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr>
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Berglunds snabbköp</td>
        <td>Christina Berglund</td>
        <td>Sweden</td>
      </tr>
      <tr>
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr>
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
      <tr>
        <td>Island Trading</td>
        <td>Helen Bennett</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Königlich Essen</td>
        <td>Philip Cramer</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Laughing Bacchus Winecellars</td>
        <td>Yoshi Tannamuri</td>
        <td>Canada</td>
      </tr>
      <tr>
        <td>Magazzini Alimentari Riuniti</td>
        <td>Giovanni Rovelli</td>
        <td>Italy</td>
      </tr>
      <tr>
        <td>North/South</td>
        <td>Simon Crowther</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Paris spécialités</td>
        <td>Marie Bertrand</td>
        <td>France</td>
      </tr>
</table><br>
    <!--Bordered table:-->
    <table class="tl-br">
    <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr>
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Berglunds snabbköp</td>
        <td>Christina Berglund</td>
        <td>Sweden</td>
      </tr>
      <tr>
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr>
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
      <tr>
        <td>Island Trading</td>
        <td>Helen Bennett</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Königlich Essen</td>
        <td>Philip Cramer</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Laughing Bacchus Winecellars</td>
        <td>Yoshi Tannamuri</td>
        <td>Canada</td>
      </tr>
      <tr>
        <td>Magazzini Alimentari Riuniti</td>
        <td>Giovanni Rovelli</td>
        <td>Italy</td>
      </tr>
      <tr>
        <td>North/South</td>
        <td>Simon Crowther</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Paris spécialités</td>
        <td>Marie Bertrand</td>
        <td>France</td>
      </tr>
</table><br>
    <!--Striped in hover table:-->
    <table class="tl-hr">
    <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr>
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Berglunds snabbköp</td>
        <td>Christina Berglund</td>
        <td>Sweden</td>
      </tr>
      <tr>
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr>
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
      <tr>
        <td>Island Trading</td>
        <td>Helen Bennett</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Königlich Essen</td>
        <td>Philip Cramer</td>
        <td>Germany</td>
      </tr>
      <tr>
        <td>Laughing Bacchus Winecellars</td>
        <td>Yoshi Tannamuri</td>
        <td>Canada</td>
      </tr>
      <tr>
        <td>Magazzini Alimentari Riuniti</td>
        <td>Giovanni Rovelli</td>
        <td>Italy</td>
      </tr>
      <tr>
        <td>North/South</td>
        <td>Simon Crowther</td>
        <td>UK</td>
      </tr>
      <tr>
        <td>Paris spécialités</td>
        <td>Marie Bertrand</td>
        <td>France</td>
      </tr>
</table><br>
    <table class="tl-spd">
    <tr>
        <th>Company</th>
        <th>Contact</th>
        <th>Country</th>
      </tr>
      <tr class="tw-sc">
        <td>Alfreds Futterkiste</td>
        <td>Maria Anders</td>
        <td>Germany</td>
      </tr>
      <tr class="tl-i">
        <td>Berglunds snabbköp</td>
        <td>Christina Berglund</td>
        <td>Sweden</td>
      </tr>
      <tr class="tl-dg">
        <td>Centro comercial Moctezuma</td>
        <td>Francisco Chang</td>
        <td>Mexico</td>
      </tr>
      <tr class="tl-at">
        <td>Ernst Handel</td>
        <td>Roland Mendel</td>
        <td>Austria</td>
      </tr>
    </table>
  </body>
</html>
```
### Images in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <!--Rounded Corners:-->
    <img src="https://www.nps.gov/articles/images/Image-w-cred-cap_-1200w-_-Brown-Bear-page_-brown-bear-in-fog_2_1.jpg?maxwidth=1200&maxheight=1200&autorotate=false" class="im-rd" style="width: 800px;height: 400px;">
    <!--Circle:-->
    <img src="https://www.nps.gov/articles/images/Image-w-cred-cap_-1200w-_-Brown-Bear-page_-brown-bear-in-fog_2_1.jpg?maxwidth=1200&maxheight=1200&autorotate=false" class="im-cl" style="width: 800px;height: 400px;">
    <!--Thumbnail:-->
    <img src="https://www.nps.gov/articles/images/Image-w-cred-cap_-1200w-_-Brown-Bear-page_-brown-bear-in-fog_2_1.jpg?maxwidth=1200&maxheight=1200&autorotate=false" class="im-tm" style="width: 800px;height: 400px;">
    <!--Opacity:-->
    <img src="https://www.nps.gov/articles/images/Image-w-cred-cap_-1200w-_-Brown-Bear-page_-brown-bear-in-fog_2_1.jpg?maxwidth=1200&maxheight=1200&autorotate=false" class="im-op-5" style="width: 800px;">
    <!--Card:-->
      <div class="im-tm">
    <img src="https://www.nps.gov/articles/images/Image-w-cred-cap_-1200w-_-Brown-Bear-page_-brown-bear-in-fog_2_1.jpg?maxwidth=1200&maxheight=1200&autorotate=false">
    <div class="im-ca">Hello, world!</div>
  </div><br>
  </body>
</html>
```
### Heading in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="hd-jm">Stylezator framework
    <div class="hd-lt">This framework it's very simple and new UI framework</div>
    </div><br>
    <div class="hd-ht">
      UI frameworks
    </div>
```
### Wells in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="wl-bc">Basic well</div><br>
    <div class="wl-sml">small well</div><br>
    <div class="wl-nml">normal well</div><br>
    <div class="wl-lrg">large well</div><br>
  </body>
</html>
```
### Alerts in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
<div class="ms-sc">
      <b>Success</b> success message! <a class="ms-an" href="#">anchor alert</a>
    </div><br>
    <div class="ms-in">
      <b>Info</b> info message! <a class="ms-an" href="#">anchor alert</a>
    </div><br>
    <div class="ms-wr">
      <b>Warning</b> warning message! <a class="ms-an" href="#">anchor alert</a>
    </div><br>
    <div class="ms-dr">
      <b>Danger</b> danger message! <a class="ms-an" href="#">anchor alert</a>
    </div><br>
  </body>
</html>
```
### Buttons in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <a class="btn-bc">Basic</a> <a class="btn-dt">Default</a> <a class="btn-pr">Primary</a> <a class="btn-sc">Success</a> <a class="btn-i">Info</a> <a class="btn-wr">Warning</a> <a class="btn-dn">Danger</a> <a class="btn-ln">Link</a><br><br>
    <a class="btn-bc-xs">Xsmall</a> <a class="btn-wr-s">Small</a> <a class="btn-dn-n">Normal</a> <a class="btn-sc-lg">Large</a><br><br><br>
    <!--Level buttons:-->
    <a class="btn-pr-lv">Level button</a><br><br><br>
    <a class="btn-dn-lv">Level button</a><br><br><br>
    <a class="btn-sc-lv">Level button</a><br>
  </body>
</html>
```
### Badges and labels in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <!--Badges:-->
    Notifacation<span class="bdg">4</span><br><br>
    <a class="btn-pr">Notifacitons <span class="bdg-pr">4</span></a><br><br>
    <a class="btn-dt">Notifacitons <span class="bdg-dt">4</span></a><br><br>
    <a class="btn-sc">Notifacitons <span class="bdg-sc">4</span></a><br><br>
    <!--Label:-->
    <h5>Hello, world <span class="lbl">danger</span></h5>
  </body>
</html>
```
### Progress bars in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="pb">
      <div  class="pb-com" role="progressbar" aria-valuenow="70"
      aria-valuemin="0" aria-valuemax="100" style="width:70%">70%</div>
    </div><br>
    <div class="pb">
      <div  class="pb-com bg-sc" role="progressbar" aria-valuenow="70"
      aria-valuemin="0" aria-valuemax="100" style="width:50%">70%</div>
    </div><br>
  </body>
</html>
```
### Pager and breadcrumb in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <!--Pager:-->
  <div class="pgn">
    <a href="#">&laquo;</a>
    <a href="#" class="act">1</a>
    <a href="#">2</a>
    <a href="#">3</a>
    <a href="#">4</a>
    <a href="#" class="dsb">5</a>
    <a href="#">&raquo;</a>
  </div><br><br>
    <!--Breadcrumb:-->
      <ul class="bcm">
    <li><a href="#">Styleator</a>
    <li><a href="#examples">Examples</a>
      <li><a href="#">Docs</a>
      <li>Me
  </ul>
  </body>
</html>
```
### Previous and next buttons (pager) in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
  <div class="pgr">
    <a href="#" class="prev">Prevoius</a>
    <a href="#" class="next">Next</a>
  </div>
  </body>
</html>
```
### List groups in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
   <ul class="li-grp">
      <li class="li-t">Facebook</li>
      <li class="li-t">Instagram</li>
      <li class="li-t">Twitter</li>
    </ul><br>
    <!--Hovered list group:-->
    <ul class="li-grp-hr">
      <li class="li-t-hr">Facebook</li>
      <li class="li-t-hr-act">Instagram</li>
      <li class="li-t-hr">Twitter</li>
    </ul><br>
  </body>
</html>
```
### Panels in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="pl-hd">Panel header</div>
    <div class="pl-dt">Text</div>
    <div class="pl-ft">Panel footer</div>
  </body>
</html>
```
### Dropdowns in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
    <div class="dropdown">
      <button onclick="dropdown()" class="dropbtn">Dropdown</button>
      <div id="myDropdown" class="dropdown-content">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </div>
  </body>
</html>
```
### Collapse in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
  <button class="collapsible" data-toggle="collapse" data-target="#demo">Open Collapsible</button>
  <div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud               exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  </div>
  </body>
</html>
```
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
### Forms and inputs in stylezator
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
<div class="fr-hor">
  Email: <input placeholder="Email" class="fr-hr-inp"><br>
  Password: <input placeholder="Password" class="fr-hr-inp">
</div>
  </body>
</html>
```
### Stylezator filter
```markdown
<!DOCTYPE html>
<html>
  <head>
    <title>Document</title>
    <link rel="stylesheet" href="main/sty_css.css">
    <script src="main/sty-js.js"></script>
  </head>
  <body>
<input type="text" id="myInput" onkeyup="myFilter()" placeholder="Search for names..">

<ul id="myUL">
  <li><a href="#">Adele</a></li>
  <li><a href="#">Agnes</a></li>

  <li><a href="#">Billy</a></li>
  <li><a href="#">Bob</a></li>

  <li><a href="#">Calvin</a></li>
  <li><a href="#">Christina</a></li>
  <li><a href="#">Cindy</a></li>
</ul>
  </body>
</html>
```
### Warning
Because this framework does not have online codes, you will need to download it from github.
### About creators
Powered by Stylezator Group Inc copyright 2021. All rights reserved. Author: Jahongir Sobirov. 
