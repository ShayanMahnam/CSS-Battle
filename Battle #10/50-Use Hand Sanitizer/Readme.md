```html
<div id="e"></div>
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  *{
    background:#1A4341;
  }
  #a {
    width: 100px;
    height: 105px;
    background: #998235;
    border-radius:0 0 20px 20px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -5%);
  }
  #a:after {
    content:'';
    height: 60px;
    width: 100px;
    background: #F3AC3C;
    border-radius:20px 20px 0 0;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -145%);
  }
  #b {
    width: 20px;
    height: 20px;
    background:#998235;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(400%,-250%);
    box-shadow: 0 30px #998235;
  }
  #c {
    width:50px;
    height:80px;
    background:#998235;
    border-radius:40px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-100%, -12%);
    box-shadow: 50px -30px #F3AC3C;
  }
  #d {
    width:50px;
    height:20px;
    background:#F3AC3C;
    border-radius:10px 10px 0 0;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-297%)
  }
  #e {
    width:150px;
    height:20px;
    background:#F3AC3C;
    border-radius:10px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-33%,-500%)
  }
  #e:before {
    content:'';
    width:150px;
    height:20px;
    background:#F3AC3C;
    border-radius:10px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-67%,300%) rotate(90deg);
  }
  #e:after {
    content:'';
    width:40px;
    height:20px;
    background:#F3AC3C;
    border-radius:10px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(115%,5%) rotate(90deg)
  }
</style>
```