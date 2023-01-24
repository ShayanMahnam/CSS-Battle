```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  body{background:#191919}
  #a {
    width: 48px;
    height: 44px;
    background:#E08027;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-53%,40%) rotate(45deg)
  }
  #b, #b:before{
    width:114px;
    height:114px;
    background:#E08027;
    border-radius:0% 50% 50% 50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-97%,-64%);
  }
  #b:before{
    content:'';
    transform: scaleX(-1)translate(-40px, -67px);
    border:10px solid #191919;
  }
  #c{
    width:90px;
    height:90px;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-110%,-68%);
  box-shadow: 108px 0 #191919;
  }
  #d,#d:after{
    width:13px;
    height:13px;
    border:8px solid #E08027;
    border-color: #E08027 #E08027 transparent transparent;
    border-radius:50%;
    
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-236%,-85%) rotate(-45deg);
  }
  #d:after{
    content:'';
    transform: rotate(0) translate(62px,62px)
  }
</style>
```