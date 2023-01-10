```html
<div id="c"></div>
<div id="a"></div>
<div id="b"></div>

<style>
  *{background:#1A4341}
  #a {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
    border-radius:50%;
  }
  #b, #b:before, #b:after {
    width: 30px;
    height: 30px;
    background: #998235;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
transform:translate(-100%,-100%);
  }
  #b:before,#b:after {
    content:'';
  }
  #b:before{
    width: 20px;
    height: 20px;
    top:50%;
    left:50%;
transform:translate(25%,150%);
  }
  #b:after{
    width: 10px;
    height: 10px;
    top:50%;
    left:50%;
transform:translate(350%,-150%);
  }
  #c, #c:before, #c:after{
    width:10px;
    height:180px;
    background:#F3AC3C;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-55%);
  }
  #c:before, #c:after{
    content:'';
    transform:translate(4px,-48%) rotate(60deg)
  }
  #c:after{
    transform:translate(40%,-42%) rotate(-60deg)
  }
</style>
```