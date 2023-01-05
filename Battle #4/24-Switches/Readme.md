```html
<div id="b"></div>
<div id="a"></div>

<style>
  *{
    background:#62306D
  }
  #a,#a:before {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    border-radius:50%;
    position:absolute;
    left:80px;
    top:100px;
  }
  #a:before{
    content:'';
    left:140px;
    top:0;
  }
  #b,#b:before {
    width: 100px;
    height: 150px;
    background: #AA445F;
    border-radius:100px 100px 100px 100px;
    position:absolute;
    left:80px;
    top:50px;
  }
  #b:before{
    content:'';
    left:140px;
    top:50px;
    background:#E38F66
  }
</style>
```