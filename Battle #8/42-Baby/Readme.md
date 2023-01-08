```html
<div id="a">
  <div id="c"></div>
</div>
<div id="b"></div>

<style>
  *{
    background:#293462;
  }
  #a {
    width: 200px;
    height: 200px;
    background: #FE5F55;
    border-radius:50% 50% 50px 50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
    overflow:hidden;
  }
  #a:after{
    content:'';
    width: 40px;
    height: 10px;
    background: #FFF1C1;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,700%);
  }
  #b{
    width:59px;
    height:59px;
    background:#FFF1C1;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-135%,-16%);
    box-shadow: 100px 0 #FFF1C1;
  }
  #C{
    width:100px;
    height:120px;
    background: #FFF1C1;
    border-radius:50px 50px 50px 50px;
    position:absolute;
    top:50%;
    left:50%;
transform:translate(-100%,-142%);
    box-shadow:100px 0 #FFF1C1;
  }
</style>
```