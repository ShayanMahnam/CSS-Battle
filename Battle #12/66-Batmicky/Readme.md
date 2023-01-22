```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>

<style>
  body{background:#191919}
  #a,#a:before,#a:after{
    width: 250px;
    height: 100px;
    background: #F2AD43;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%)
  }
  #a:before {
    content:'';
    width:80px;
    height:50px;
    background:#191919;
    border-radius:10px;    
  transform:translate(-50%,-140%)
  }
  #a:after {
    content:'';
    width:20px;
    height:20px;
    background:#F2AD43;
  transform:translate(-50%,-200%)
  }
  #b{
    width:100px;
    height:100px;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-175%,-50%);
    -webkit-box-reflect: right 150px;
  }
  #c{
   width:200px;
    height:200px;
    background:#191919;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-80%,5%);
    -webkit-box-reflect: right -80px;
  }
  #d{
    width:10px;
    height:10px;
    background:#F2AD43;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-150%,-450%);
    box-shadow: 20px 0 #F2AD43;
  }
</style>
```