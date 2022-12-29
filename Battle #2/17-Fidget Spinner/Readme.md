```html
<div id="r"></div>
<div id="c"></div>
<div id="c2"></div>
<style>
  body{ background:#09042A}
  #r{
    width: 60px;
    height: 60px;
    background: #E78481;
    position:absolute;
    top:120px;
    left:170px;
  }
  #c, #c:before {
    width: 60px;
    height: 60px;
    background: #09042A;
    border-radius: 50%;
    border: 10px solid #E78481;
    position:absolute;
    top: 110px;
    left: 100px;
  }
  #c:before{
    content:'';
    top: -10px;
    left:110px;
  }
  #c2, #c2:before {
    width: 60px;
    height: 60px;
    background: #F5BB9C;
    border-radius: 50%;
    border: 10px solid #09042A;
    position:absolute;
    top: 57px;
    left: 160px;
  }
  #c2:before{
    content:'';
    top:96px;
    left:-10px;
  }
</style>
```