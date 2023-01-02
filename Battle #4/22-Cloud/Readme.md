```html
<div id="c"></div>

<style>
  *{
  background:#F5D6B4;  
  }
  #c, #c:before, #c:after {
    width: 100px;
    height: 100px;
    background: #D86F45;
    border-radius:50%;
    position:absolute;
    top:115px;
    left:100px
  }
  #c:before{
    content:'';
    top:-30px;
    left:80px;
  }
  #c:after{
    content:'';
    width: 180px;
    height: 50px;
    border-radius: 50px;
    top: 50px;
    left:20px;
  }
</style>
```