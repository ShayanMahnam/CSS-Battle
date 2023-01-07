```html
<div id="b"></div>
<div id="a"></div>

<style>
  *{
    background:#293462;
  }
  #a {
    width: 100px;
    height: 150px;
    background: #FFF1C1;
    border-radius:100px 100px 40px 40px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-67%);
  }
  #b{
    background:#FE5F55;
    width:30px;
    height:40px;
    border-radius:0px 0px 10px 10px;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,150%);
  }
  #b:before{
    content:'';
    width:30px;
    height:10px;
    background:#A64942;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-300%);
  }
</style>
```