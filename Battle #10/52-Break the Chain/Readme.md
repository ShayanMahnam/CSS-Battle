```html
<div id="b"></div>
<div id="a"></div>

<style>
  *{
    background:#6592CF;
  }
  #a,#a:after {
    width: 10px;
    height: 50px;
    background: #243D83;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(100%,-20%);
    box-shadow: 45px 0 #243D83,90px 0 #243D83,135px 0 #243D83,-75px 0 #243D83,-120px 0 #243D83,-165px 0 #243D83;
  }
  #a:after {
    content:'';
    width:20px;
    height:20px;
    border-radius:50%;
    transform:translate(-50%,-175%)
  }
  #b,#b:before {
    width:60px;
    height:60px;
    background:#EEB850;
    border-radius:50%;
     position:absolute;
    top:50%;
    left:50%;
    transform:translate(-225%,-85%);
  }
  #b:before{
    content:'';
    width:40px;
    height:40px;
    transform:translate(-163%,-25%);
    box-shadow: 90px 0 #EEB850;
  }
</style>
```