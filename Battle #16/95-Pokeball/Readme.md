```html
<div id="d"></div>
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  body{
    background:#6CB3A9;
  }
  #d{
    width: 180px;
    height: 100px;
    background:#781728;
    position:absolute;
    border-radius:10px;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #a {
    width: 200px;
    height: 200px;
    background: #D25B70;
  clip-path: polygon(0 0, 100% 0, 100% 45%, 0 45%);
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #b{
    width: 200px;
    height: 200px;
    background: #FFFFFF;
    clip-path: polygon(0 55%, 100% 55%, 100% 100%, 0 100%);
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #c{
    width:50px;
    height:50px;
    background:#F6DF96;
    border:10px solid #781728;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
</style>
```