```html
<div id="a"></div>
<div id="b"></div>

<style>
  *{
    background:#1A4341;
  }
  #a {
    width: 50px;
    height: 50px;
    background: #F3AC3C;
    border-radius: 100px 100px 0 0;
    position:absolute;
    top: 90px;
    left: 140px;
    box-shadow: 70px 0px #998235;
  }
  #a:before{
    content:'';
    width: 50px;
    height: 50px;
    background: #F3AC3C;
    border-radius: 0 0 100px 100px;
    position:absolute;
    top: 70px;
    left: -70px;
    box-shadow: 210px 0px #998235;
  }
  #b {
    width: 50px;
    height: 50px;
    background: #998235;
    border-radius: 50%;
    position:absolute;
    top: 90px;
    left: 70px;
    box-shadow: 210px 0px #F3AC3C;
  }
  #b:before{
    content:'';
    width: 50px;
    height: 50px;
    background: #998235;
    border-radius: 50%;
    position:absolute;
    top: 70px;
    left: 70px;
    box-shadow: 70px 0px #F3AC3C;
  }
</style>
```