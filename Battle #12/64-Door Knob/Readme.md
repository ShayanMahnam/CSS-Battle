```html
<div ></div>
<div ></div>

<style>
  body{background:#191919}
  div {
    width: 100px;
    height: 100px;
    background: #E08027;
    border:30px solid #824B20;
    border-radius:50%;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%)
  }
  div:before {
    content:'';
    border: 20px solid #FFF58F;
    width:80px;
    height:80px;
    border-radius:50%;
    border-color:transparent transparent #FFF58F #FFF58F;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,-50%) rotate(-45deg)
  }
  div:after{
    content:'';
    width:20px;
    height:20px;
    background:#FFF58F;
    position:absolute;
    left:50%;
    top:50%;
    border-radius:50%;
    transform:translate(-300%,-50%);
    box-shadow:100px 0 #FFF58F;
  }
</style>
```