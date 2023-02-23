```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  body{
    background:#998235;
  }
  #a {
    width: 180px;
    height: 100px;
    background: #191919;
    border-radius:10px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #b{
    width: 20px;
    height: 70px;
    background: #FFFFFF;
    border-radius:5px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-425%,-35%);
    box-shadow: 25px 0 #FFFFFF,50px 0 #FFFFFF,75px 0 #FFFFFF,100px 0 #FFFFFF,125px 0 #FFFFFF,150px 0 #FFFFFF;
  }
  #c{
    width: 15px;
    height: 40px;
    background: #191919;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-465%,-75%);
    box-shadow:25px 0 #191919,75px 0 #191919,100px 0 #191919,125px 0 #191919;
  }
</style>
```