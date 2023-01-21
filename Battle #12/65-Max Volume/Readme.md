```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  body{background:#191919}
  #a,#a:before,#a:after {
    border: 10px solid #FFF58F;
    width:80px;
    height:80px;
    border-radius:50%;
    border-color:transparent transparent #5DBCF9 #5DBCF9;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-25%,-50%) rotate(-135deg)
  }
  #a:before{
    content:'';
    width:130px;
    height:130px;
    transform:translate(-50%,-50%)
  }
  #a:after{
    content:'';
    width:180px;
    height:180px;
    transform:translate(-50%,-50%)
  }

  #b{
    width:50px;
    height:50px;
    background:#5DBCF9;
    border-radius:10px 0 0 10px;
    position:absolute;
    left:50%;
    top:50%;
  transform:translate(-250%,-50%);
  }
  #c{
    border-bottom:100px solid transparent;
    border-top:100px solid transparent;
    border-right:100px solid #5DBCF9;
    position:absolute;
    bottom:50px;
    left:50%;
    transform:translate(-100%,0%);
  }
</style>
```