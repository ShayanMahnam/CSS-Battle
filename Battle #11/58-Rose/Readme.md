```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  *{background:#191919}
  #a,#a:after {
    width: 20px;
    height: 80px;
    background: #F9E492;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,30%);
  }
  #a:after{
    content:'';
    width:40px;
    height:40px;
    top:-50%;
  }
  #b{
    width:100px;
    height:100px;
    background:linear-gradient(#191919 60%, #4F77FF 50%);
    border-radius: 50%;
    position:absolute;
    top:50%;
    left:50%;
 transform:translate(-50%,-85%);
  }
  #c,#c:after{
    width:140px;
    height:30px;
    background:#4F77FF;
    border-radius:6px 6px 50px 50px;
    position:absolute;
    top:50%;
    left:50%;
 transform:translate(-50%,-215%);
  }
  #c:after{
    content:'';
    width:100px;
    height:30px;
    top:145%;
    border-radius:6px 6px 30px 30px;
    box-shadow: 0 0 0 10px #191919;
  }
  #d {
    width:30px;
    height:30px;
    background:#4F77FF;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
 transform:translate(-50%,-350%);
    box-shadow: 0 0 0 10px #191919;
  }
</style>
```