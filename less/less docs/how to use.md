## How to use Stylezator less plugin?
With this plugin you can add a stylezator style to your style created in less.
```less
//use myless plugin:

@import "myless.less"

.mycontainer{
  background-color: @info;
  font-family: @t-font;
}
ul{
  font-family: @t-font;
  li{
    list-style-type: @list-roman;
  }
}
```
