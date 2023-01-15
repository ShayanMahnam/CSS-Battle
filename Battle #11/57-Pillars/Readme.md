```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  *{
    background:#191919;
  }
  #a {
    width: 110px;
    height: 110px;
    background: #4F77FF;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #b{
    width: 60px;
    height: 60px;
    background: #191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
transform:translate(-125%,-125%);
    box-shadow: 90px 0 #191919,90px 90px #191919,0 90px #191919;
  }
  #c {
    width: 45px;
    height: 45px;
    background: #F9E492;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
transform:translate(-167%,-167%);
    box-shadow: 105px 0 #F9E492,105px 105px #F9E492,0 105px #F9E492;
  }
  #d {
    width: 30px;
    height: 30px;
    background: #4F77FF;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
transform:translate(-250%,-250%);
    box-shadow: 120px 0 #4F77FF,120px 120px #4F77FF,0 120px #4F77FF;
  }
</style>
```