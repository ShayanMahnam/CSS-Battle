```html
<div id="a"></div>
<div id="b"></div>

<style>
  *{background:#6592CF}
  #a {
    width: 200px;
    height: 200px;
    background: #243D83;
    border-radius:0 50% 50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -50%)
  }
  #a:after{
    content:'';
    width:100px;
    height:100px;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -50%);
    background:#6592CF;
  }
  #b{
    width:50px;
    height:100px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-100%, -100%);
    background:#6592CF
  }
</style>
```