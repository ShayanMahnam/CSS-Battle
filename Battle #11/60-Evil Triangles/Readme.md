```html
<div></div>

<style>
  body{
    background:#191919;
  }
  :before,:after{
    content:'';
    position:absolute;
    border-left:50px solid transparent;
    border-right:50px solid transparent;
  }
  div {
    width: 100px;
    height: 100px;
    background: linear-gradient(#191919  50%,#4F77FF 50%);
    position:absolute;
    top:75px;
    right:50%;
    -webkit-box-reflect: right;
  }
  div:before{
    border-top:50px solid #4F77FF;
  }
  div:after{
    border-top:50px solid #191919;
    bottom:0;
  }
  body:before{
    bottom:75px;
    right:50%;
    border-top:50px solid #4F77FF;
    -webkit-box-reflect: right;
  }
  
</style>
```