```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  body{
    background:#6592CF;
  }
  #a {
    width: 170px;
    height: 170px;
    box-shadow: inset 0 0 0 10px #243D83;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-44%);
    overflow:hidden;
  }
  #a:after{
    content:'';
    width: 100px;
    height: 100px;
    background:#6592CF;
    border:10px solid #243D83;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,33%)
  }
  #b,#b:after{
    width: 10px;
    height: 10px;
    background:#243D83;
    border: 10px solid #6592CF;
    outline:10px solid #243D83;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-285%,-150%);
    -webkit-box-reflect: right 110px;
  }
  #b:after{
    content:'';
    transform: translate(-50%,183%);
  }
  #c{
    width: 10px;
    height: 10px;
    background:#243D83;
    border: 10px solid #6592CF;
    outline:10px solid #243D83;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-283%);
  }
</style>
```