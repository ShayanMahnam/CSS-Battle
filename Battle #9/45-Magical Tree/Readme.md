```html
<div id="b"></div>
<div id="a"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  *{
    background:#1A4341;
  }
  #a {
    width: 90px;
    height: 120px;
    background: #1A4341;
    position:absolute;
    top:0;
    left:50%;
    transform:translate(-50%,0);
    border: 30px solid #998235;
    outline:30px solid #1A4341;
    border-top:0;
  }
  #b{
    width: 270px;
    height: 210px;
    background: #F3AC3C;
    position:absolute;
    top:0;
    left:50%;
    transform:translate(-50%,0);
  }
  #c{
    width: 270px;
    height: 30px;
    background: #998235;
    position:absolute;
    bottom:30px;
    left:50%;
    transform:translate(-50%,0);
  }
  #d{
    width: 30px;
    height: 100vh;
    background:#F3AC3C;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
  }
</style>
```