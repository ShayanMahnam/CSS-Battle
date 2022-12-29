```html
<div id="l" class></div>
<div id="c"></div>
<div id="r"></div>

<style>
  body{
    background:#191210;
  }
 #c {
    width: 50px;
    height: 50px;
    background: #84271C;
    border-radius:100%;
    position:absolute;
    top:100px;
    left:150px;
    border: 25px solid #191210;
    outline: 20px solid #ECA03D;
  }

  #l {
    width: 60px;
    height: 30px;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
    border: 20px solid #ECA03D;
    border-top: 0;
    position: absolute;
    top:150px;
    left:50px;
  }
  #r {
    width: 60px;
    height: 30px;
    border-top-left-radius: 50px;
    border-top-right-radius: 50px;
    border: 20px solid #ECA03D;
    border-bottom: 0;
    position: absolute;
    top:100px;
    right:50px;
  }
</style>
```