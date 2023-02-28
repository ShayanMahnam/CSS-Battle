```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  body{
    background:#243D83;
  }
  #a{
    width: 100px;
    height: 50px;
    background: #6592CF;
    border-radius:50px 50px 0 0;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-110%,-170%) rotate(-45deg);
    -webkit-box-reflect: above -220px
  }

  #b{
    width: 100px;
    height: 50px;
    background: #6592CF;
    border-radius:50px 50px 0 0;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(10%,-170%) rotate(45deg);
    -webkit-box-reflect: above -220px;
  }
  #c{
    width: 60px;
    height: 60px;
    background: #EEB850;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%) 
  }
</style>
```