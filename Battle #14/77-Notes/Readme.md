```html
<div id="c"></div>
<div id="b"></div>
<div id="a"></div>

<style>
  body{
    background:#191919;
  }
  #a {
    width: 50px;
    height: 40px;
    background: #FE5F55;
    border-radius:50%;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-290%,50%);
    box-shadow: 70px 0 #FE5F55,210px 0 #FE5F55,140px 0 #A64942;
  }
  #b{
    width:60px;
    height:90px;
    border:10px solid #FE5F55;
    border-bottom:none;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-131%,-60%);
  }
  #c{
    width:30px;
    height:90px;
    border:10px solid #A64942;
    border-bottom:none;
    border-right:none;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(89%,-60%);
    filter: drop-shadow(69px 0 #FE5F55);
  }
  #b:after{
    content:'';
    width:40px;
    height:10px;
    background:#FE5F55;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(425%,-340%);
  }
  
</style>
```