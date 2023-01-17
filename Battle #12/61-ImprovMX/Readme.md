```html
<div a></div>
<div b></div>
<div c><span></span></div>

<style>
  body{background:#191919}
 div,span,:before,:after{
    content:'';
    position:absolute;
    left:50%;
    transform:translateX(-50%)
  }
  body:after {
    width: 200px;
    height: 10px;
    background: #5DBCF9;
    bottom:86px
  }
  body:before{
    width:110px;
    height: 10px;
    background: #5DBCF9;
    bottom:66
  }
  [a]{
    border:10px solid #5DBCF9;
    width: 30px;
    height: 20px;
    top:66;
  }
  [b]{
    border:10px solid #5DBCF9;
    width: 80px;
    height: 50px;
    top:96;
    border-bottom: 0
  }
  [c]{
    width: 200px;
    height: 68px;
    top:126;
    clip-path: polygon(50% 0, 100% 84%, 100% 100%, 0 100%, 0 84%)
  }
  [c]:before{
    border:10px solid #5DBCF9;
    border-color:#5DBCF9 #5DBCF9 transparent transparent;
    width: 70px;
    height: 40px;
    transform-origin:0 0;
    transform:rotate(30deg)
  }
  [c]:after{
    left:auto;
    right:50%;
    width: 70px;
    height: 40px;
    border:10px solid #5DBCF9;
    border-color:#5DBCF9 transparent transparent #5DBCF9;
    transform-origin:100% 0;
    transform:rotate(-30deg)
  }
  span{
    width: 10px;
    height: 100%;
    background:#5DBCF9;
  }
</style>
```