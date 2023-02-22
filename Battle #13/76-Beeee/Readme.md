```html
<div id="a">
  <div id="b"></div>
</div>
<div id="c"></div>

<style>
  body{
    background:#998235;
  }
  #a {
    width: 150px;
    height: 75px;
    background: #EFF33C;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,0%);
    overflow:hidden;
  }
  #b{
    width:25px;
    height:75px;
    background:#191919;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-20%,-50%);
    box-shadow:-35px 0 #191919,-70px 0 #191919;
  }
  #b:after{
    content:'';
    width:15px;
    height:15px;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(215%,-115%);
  }
  #c{
    width: 75px;
    height: 75px;
    background: #FFFFFF;
    border-radius:50px 50px 0 50px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-100%,-100%);
    -webkit-box-reflect: right 0;
  }
  
</style>
```