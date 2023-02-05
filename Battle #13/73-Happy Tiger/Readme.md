```html
<div id="b"></div>
<div id="a">
  <div id="e"></div>
</div>
<div id="c"></div>
<div id="d"></div>
<div id="f"></div>

<style>
  body{
    background:#F3AC3C;
  }
  #a {
    width: 150px;
    height: 150px;
    background: #998235;
    border-radius:100px 100px 80px 80px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    overflow:hidden;
  }
  #e{
    width: 50px;
    height: 50px;
    background: #1A4341;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-220%) rotate(45deg);
  }
  #b{
    width: 40px;
    height: 40px;
    background: #1A4341;
    border-radius:50%;
    border:10px solid #998235;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-142%,-142%);
    -webkit-box-reflect: right 50px;
  }
  #c{
    width: 20px;
    height: 20px;
    background: #1A4341;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-250%,-75%);
    -webkit-box-reflect: right 60px;
  }

  #d{
    width: 50px;
    height: 40px;
    background: #FFFFFF;
    border-radius:20px 0px 0px 50px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-100%,50%);
    -webkit-box-reflect: right ;
  }

  #d:after{
    content:'';
    width:20px;
    height:40px;
    border:10px solid #1A4341;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-25%,-83%);
    clip-path: polygon(0 100%, 100% 100%, 100% 20px,50% 20px,50% 40px, 0 40px);  
  }
</style>
```