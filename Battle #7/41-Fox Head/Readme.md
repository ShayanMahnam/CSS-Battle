```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  *{background:#293462}
  #a, #a:after {
    width: 50px;
    height: 140px;
    background: #FE5F55;
    border-radius: 0 40px 0px 0;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-100%,-50%);
  }
  #a:after{
    content:'';
    transform:translate(50%,-50%) scaleX(-1);
  }
  #b, #b:after {
    width: 50px;
    height: 140px;
    background: #293462;
    border-radius: 0 40px 0px 0;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-100%,21%);
  }
  #b:after{
    content:'';
    transform:translate(50%,-50%) scaleX(-1);
  }
  #c{
    width:30px;
    height:30px;
    background:#293462;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-115%,-34%);
    box-shadow: 40px 0 #293462;
  }
</style>
```