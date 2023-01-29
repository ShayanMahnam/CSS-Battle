```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>

<style>
  *{background:#293462}
  #a {
    width: 150px;
    height: 100px;
    background: radial-gradient(circle at 50% -130px,#FE5F55 200px,#A64942 200px);
    border-radius:50px;
    position:absolute;
    top: calc(50% + 10px);
    left:50%;
    transform:translate(-50%,-50%)
  }
  #b{
    width:10px;
    height:10px;
    background:#293462;
    border-radius:50%;
    border:10px solid #FFF1C1;
    outline:10px solid #FE5F55;
     position:absolute;
    top: 50%;
    left:50%;
  transform:translate(-171%,-185%);
   -webkit-box-reflect: right 40px; 
  }
  #c{
    width:10px;
    height:10px;
    background:#293462;
    border-radius:50%;
    position:absolute;
    top: 50%;
    left:50%;
  transform:translate(50%,100%);
    box-shadow: -20px 0 #293462;
  }
</style>
```