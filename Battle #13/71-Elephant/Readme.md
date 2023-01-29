```html
<div id="b"></div>
<div id="a"></div>
<div id="c"></div>
<div id="d"></div>
<div id="e"></div>
<div id="f"></div>

<style>
  body{background:#998235}
  #a {
    width: 180px;
    height: 180px;
    background: #1A4341;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #b{
    width: 81px;
    height: 180px;
    background: #0B2429;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-186%,-50%);
    box-shadow: inset 17px 0 0 0 #1A4341;
    -webkit-box-reflect: right 139px
  }
  #c,#c:after{
    width: 40px;
    height: 40px;
    background: #998235;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-125%,-50%);
    box-shadow: 60px 0 #998235;
  }
  #c:after{
    content:'';
    background:#0B2429;
    width: 20px;
    height: 20px;
transform:translate(-50%,-50%);
    box-shadow: 60px 0 #0B2429;
  }
  #d{
    width:100px;
    height:50px;
    background:#1A4341;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-100%)
  }
  #e{
    width:80px;
    height:80px;
    border: 20px solid #FFFFFF;
    border-radius:50%;
    clip-path:polygon(0 0, 100% 0 ,100% 50%, 0 50%);
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,33%)
  }
  #f{
    width:40px;
    height:150px;
    border-radius:50px;
    background:#0B2429;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,20%)
  }
</style>
```