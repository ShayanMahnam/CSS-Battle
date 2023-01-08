```html
<div id="a">
  <div id="b"></div>
</div>

<style>
  *{
    background:#6592CF;
  }
  #a {
    width: 110px;
    height: 100vh;
    background: #6592CF;
    position:absolute;
    top:0;
    left:145px;
    overflow:hidden;
  }
  #b{
    width:300px;
    height:182px;
    border: 30px solid #243D83;
    border-radius:70px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-96%,-50%);
    -webkit-box-reflect: right -30px ;
  }
</style>
```