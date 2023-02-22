```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>
<div id="e"></div>

<style>
  body{
    background:#191919;
  }
  #a {
    width: 130px;
    height: 100px;
    background: #FE5F55;
    position:absolute;
    left: 50%;
    top:50%;
    transform: translate(-50%,-75%);
    border-radius: 60px 60px 0 0
  }
  #b{
    width: 150px;
    height: 100px;
    background: #A64942;
    position:absolute;
    left: 50%;
    top:50%;
    transform: translate(-50%,-4%);
    border-radius: 100px 100px 90px 90px;
  }
  #c, #c:after{
    width:8px;
    height:20px;
    border: 5px solid #FE5F55;
    border-radius:50% 50% 0 0;
    position:absolute;
    left: 50%;
    top:50%;
    transform: translate(-272%,-267%) rotate(-50deg);
  }
  #c:after{
    content:'';
    transform: translate(240%,155%) rotate(100deg);
  }
  #d,#d:after{
    width:20px;
    height:30px;
    background:#000000;
    border-radius:50%;
    position:absolute;
    left: 50%;
    top:50%;
    transform: translate(-250%,50%) rotate(45deg);
  }
  #d:after{
    content:'';
     transform: translate(230%,-235%) rotate(90deg);
  }
  #e{
    width:10px;
    height:10px;
    background:#000000;
    border-radius:50%;
    position:absolute;
    left: 50%;
    top:50%;
    transform: translate(-400%,-250%);
    box-shadow:70px 0 #000000;
  }
</style>
```