```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  *{
    background:#6592CF;
  }
  #a {
    width: 150px;
    height: 120px;
    background: #243D83;
    border-radius:10px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-17%)
  }
  #b {
    width:0px;
    border-bottom:100px solid #243D83;
    border-left:100px solid transparent;
    border-right:100px solid transparent;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-100%);
  }
  #c {
    width: 100px;
    height:10px;
    background:#EEB850;
    border-radius:50px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
  }
  #d {
    width:50px;
    height:50px;
    background:#EEB850;
    border-radius:10px 10px 0 0;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,100%);
  }
</style>
```