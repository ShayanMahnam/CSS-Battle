```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  body{background:#191919}
  #a {
    width: 150px;
    height: 150px;
    background: #4F77FF;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #b{
    width:10px;
    height:200px;
    background:#191919;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #c{
    width:200px;
    height:200px;
    border:10px solid #191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-80%,-50%);
    -webkit-box-reflect:left -351px
  }
  #d{
    width:200px;
    height:10px;
    background:#191919;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
  box-shadow: 0 40px #191919, 0 -40px #191919;
  }
</style>
```