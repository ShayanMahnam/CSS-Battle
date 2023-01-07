```html
<div id="a"></div>
<div id="b"></div>

<style>
  *{background:#6592CF}
  #a, #a:after {
    width: 250px;
    height: 250px;
    background: #243D83;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
  }
  #a:after{
    content:'';
    width: 150px;
    height: 150px;
    background:#6592CF;
    transform:translate(-50%,-50%) rotate(15deg);
  }
  #b{
    width: 75px;
    height: 75px;
    background: #243D83;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%) rotate(30deg);
  }
</style>
```