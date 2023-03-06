```html
<div id="c"></div>
<div id="a"></div>
<div id="b"></div>

<style>
  body{
    background:#F3AC3C;
  }
  #c{
    width: 400px;
    height: 400px;
    background:#998235;
    border-radius: 50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-100%)
  }
  #b{
    width: 400px;
    height: 400px;
    background:#998235;
    border-radius: 50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,0%)
  }
  #a {
    width: 200px;
    height: 200px;
    background: #1A4341;
    border-radius: 50%;
    border: 25px solid #F3AC3C;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
</style>
```