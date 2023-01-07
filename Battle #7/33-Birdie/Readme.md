```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  *{
    background:#1A4341;
  }
  #a {
    width: 150px;
    height: 75px;
    background: #998235;
    border-radius: 100px 100px 0 0;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-75%,-50%) rotate(-90deg);
  }
  #b {
    width: 30px;
    height: 30px;
    background: #0B2429;
    border-radius: 50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-150%,-150%);
  }
   #c {
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    border-radius: 100px 0 0 0;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(0%,-100%) rotate(90deg);
  }
</style>
```