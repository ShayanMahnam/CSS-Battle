```html
<div id="a">
  <div id="b"></div>
</div>

<style>
  body{
    background:#191919
  }
  #a {
    width: 100px;
    height: 150px;
    background: #4F77FF;
    border-radius:50px 50px 0 0;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #b{
    width: 100px;
    height: 20px;
    background: #191919;
     position:relative;
    top:50%;
    left:50%;
    transform:translate(-30%,275%);
    box-shadow: 20px -24px #191919,40px -48px #191919,60px -72px #191919
  }
</style>
```