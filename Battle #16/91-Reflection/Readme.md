```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  #a {
    width: 400px;
    height: 150px;
    background: #D25B70;
    position:absolute;
    top:0;
    left:0;
  }
  #b {
    width: 400px;
    height: 150px;
    background: #6CB3A9;
    position:absolute;
    bottom:0;
    left:0;
  }
  #c{
    width:200px;
    height:200px;
    background:#F6DF96;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #d{
    width:210px;
    height:15px;
    background:#6CB3A9;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,0%);
    box-shadow:0 25px #6CB3A9,0 50px #6CB3A9, 0 75px #6CB3A9;
  }
</style>
```