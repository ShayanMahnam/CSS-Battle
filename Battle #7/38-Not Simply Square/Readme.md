```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  *{
    background:#293462
  }
  #a {
    width: 200px;
    height: 200px;
    background: #FFF1C1;
    position:absolute;
    left:0;
    top:0;
  }
  #b, #b:after{
    width: 100px;
    height: 200px;
    background: #FE5F55;
    position:absolute;
    left:200px;
    top:0;
  }
  #b:after{
    content:'';
    background:#A64942;
    top:150px;
    left:0px;
    height: 50px;
  }
  #c, #c:after{
    width: 200px;
    height: 100px;
    background: #FE5F55;
    position:absolute;
    left:0;
    top:200px;
  }
  #c:after{
    content:'';
    background:#A64942;
    width: 50px;
    top:0;
    left:150px;
  }
</style>
```