```html
<div id="c"></div>
<div id="a"></div>
<div id="b"></div>

<style>
  body{
    background:#243D83;
  }
  #c{
    width: 200px;
    height: 200px;
    background:#6592CF;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #a {
    width: 130px;
    height: 120px;
    border:19px solid #243D83;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-95%);
    filter:drop-shadow(0 141px #243D83);
  }
  #b {
    width: 130px;
    height: 120px;
    border:19px solid #243D83;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-8%,-50%)rotate(90deg);
    filter:drop-shadow(0 141px #243D83);
  }
</style>
```