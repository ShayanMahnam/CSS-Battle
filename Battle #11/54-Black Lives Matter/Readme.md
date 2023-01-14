```html 
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  *{background:#F9E492}
  #a,#a:after {
    width: 100px;
    height: 40px;
    background: #191919;
    border-radius:0 0 10px 10px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-30%)
  }
  #a:after{
    content:'';
    width: 50px;
    height: 70px;
    top:90%;
  }
  #b,#b:after,#b:before{
    width:20px;
    height:35px;
    background:#191919;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(150%,-150%)
  }
  #b:after,#b:before{
    content:'';
  }
  #b:before{
    height:55px;
    left:-400%;
    top:180%
  }
  #b:after{
    height:45px;
    left:-275%;
    top:165%;
    box-shadow:-50px 0 #191919;
  }
  #c{
    width:20px;
    height:65px;
    background:#191919;
    border-radius:50px;
    border:5px solid #F9E492;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-155%,-60%) rotate(60deg)
  }
</style>
```