```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  *{
    background:#191919
  }
  #a,#a:after {
    width: 120px;
    height: 100px;
    background: #4F77FF;
    border-radius: 100px 100px 20px 20px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-65%)
  }
  #a:after{
    content:'';
    width: 80px;
    height: 40px;
    border-radius: 0 0 20px 20px;
    top:115%
  }
  #b {
    width:40px;
    height:40px;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-113%,-30%);
    box-shadow:50px 0 #191919;
  }
  #b:after{
    content:'';
    width:20px;
    height:20px;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(75%,90%);
  }
  #c{
    width:10px;
    height:50px;
    background:#191919;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
   transform:translate(-50%,110%);
    box-shadow:15px 0 #191919,-15px 0 #191919;
  }
</style>
```