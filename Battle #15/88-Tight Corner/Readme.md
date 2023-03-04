```html
<div id="a"></div>
<div id="c"></div>
<div id="b"></div>

<style>
  body{
    background:#F7F3DA
  }
  #c{
    width: 40px;
    height: 40px;
    background: #D25B70;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%)
  }
  #a {
    width: 210px;
    height: 40px;
    background: #D25B70;
    border-radius:10px;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-100%,-100%);
    box-shadow:210px 40px #D25B70;
  }
  #b{
    width:50px;
    height:50px;
    background:#F7F3DA;
    border-radius:0px 30px 45px;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-0%,-100%);
    box-shadow:-50px 50px #F7F3DA;
  }
</style>
```