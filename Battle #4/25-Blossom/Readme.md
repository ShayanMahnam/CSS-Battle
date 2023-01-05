```html
<div id="a"></div>
<div id="b"></div>

<style>
  *{
    background:#998235;
  }
  #a,#a:before {
    width: 80px;
    height: 100px;
    background: #1A4341;
    border-radius:0px 50px 0px 50px;
    position:absolute;
    left:110px;
    top:60px;
  }
  #a:before{
    content:'';
    border-radius:50px 0px 50px 0px;
    left:100px;
    top:80px;
  }
  #b,#b:before {
    width: 80px;
    height: 60px;
    background: #F3AC3C;
    border-radius:50px 0px 50px 0px;
    position:absolute;
    left:210px;
    top:60px;
  }
  #b:before{
    content:'';
    border-radius:0px 50px 0px 50px;
    left:-100px;
    top:120px;
  }
</style>
```