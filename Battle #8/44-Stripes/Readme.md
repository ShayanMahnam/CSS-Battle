```html
<div id="b"></div>
<div id="a"></div>

<style>
  *{
    background:#1A4341;
  }
  #a{
    width: 300px;
    height: 300px;
    background: #1A4341;
    border-radius:50%;
    position:absolute;
    left:-150px;
    top:0px;
    box-shadow:400px 0 #1A4341;
    overlay:hidden;
  }
  #b{
    width:200px;
    height:20px;
    background:#F3AC3C;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
   box-shadow:0 40px #F3AC3C,0 80px #F3AC3C,0 -80px #F3AC3C,0 -40px #F3AC3C;
  }
</style>
```