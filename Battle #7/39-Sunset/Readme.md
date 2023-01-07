```html
<div id="a"></div>
<div id="c">
  <div id="b"></div>
</div>
<style>
  body{
    background:#1A4341;
  }
  #a {
    width: 200px;
    height: 200px;
    background: #998235;
    position:absolute;
    border-radius:50%;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #a:after{
    content:'';
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
  background:#1A4341;  
    width: 200px;
    height: 140px;
}
  #b{
    background:#F3AC3C;
    width:250px;
    height:20px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
    box-shadow: 0 40px #F3AC3C,0 -40px #F3AC3C;
  }
  #c{
    width:250px;
    height:250px;
    background:none;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
    overflow:hidden;
  }
</style>
```