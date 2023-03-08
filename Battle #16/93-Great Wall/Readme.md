```html
<div id="a">
  <div id="d"></div>
</div>
<div id="b"></div>
<div id="c"></div>

<style>
  body{
    background:#4F77FF;
  }
  #a {
    width: 200px;
    height: 200px;
    background: #191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    overflow:hidden;
  }
  #b{
    width:20px;
    height:16px;
    background:#D6B73F;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(0%,100%) skewY(-33deg);
    box-shadow:0 25px #D6B73F,0 51px #D6B73F
  }
  #c {
    width: 40px;
    height: 40px;
    background: #F9E492;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-150%,-150%)
  }
  #d{
    width:150px;
    height:15px;
    background:#F9E492;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-100%,150%);
    box-shadow:0 25px #F9E492,0 51px #F9E492,170px -13px #F9E492,170px 12px #F9E492,170px 38px #F9E492
  }
</style>
```