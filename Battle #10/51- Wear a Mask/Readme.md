```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  *{
    background:#293462;
  }
  #a {
    width: 250px;
    height: 40px;
    background: #293462;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-85%);
    border:10px solid #FFF1C1;
  }
  #b{
    width: 150px;
    height: 100px;
    background:#FFF1C1;
    border-radius:0 0 50px 50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
  }
  #c {
    width:39px;
    height:10px;
    background:#FE5F55;
    border-radius:50px;
     position:absolute;
    top:50%;
    left:50%;
transform:translate(-140%,-100%);
    box-shadow:0px -20px #FE5F55;
  }
  #d {
    width:40px;
    height:40px;
    background:#FE5F55;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
transform:translate(35%,-25%);
  }
</style>
```