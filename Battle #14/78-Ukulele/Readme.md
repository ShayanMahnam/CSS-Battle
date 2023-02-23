```html
<div id="b">
  <div id="d"></div>
</div>
<div id="c"></div>
<div id="a"></div>
<div id="e">
  <div id="f"></div>
</div>

<style>
  body{
    box-sizing:border-box;
    background:#F3AC3C;
  }
  #a {
    width: 40px;
    height: 40px;
    background: #1A4341;
    border: 5px solid #F3AC3C;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-120%,-50%);
    outline:25px solid #998235;
  }
  #b{
    width: 120px;
    height: 120px;
    background: #998235;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-130%,-50%);
  }
  #c{
    width: 120px;
    height: 20px;
    background: #1A4341;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(10%,-50%);
  }
  #d{
    width: 10px;
    height: 40px;
    background: #1A4341;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-190%,-50%);
    border-radius:50px;
  }
  #e{
    width: 40px;
    height: 30px;
    background: #998235;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(286%,-50%);
    border-radius:10px;
  }
  #f{
    width: 20px;
    height: 4px;
    background: #1A4341;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-46%,-170%);
    border-radius:50px;
    box-shadow: 0 10px #1A4341;
  }
</style>
```