```html
<div></div>
<style>
  body {
    background: #E3516E
  }
  div,div:before, div:after {
    width: 100px;
    height: 100px;
    background: #51B5A9;
    border-radius:100% 0% 0 0%;
    position: absolute;
    top: 50px;
    left: 100px
  }
  div:before ,div:after{
    content:'';
    background:#FADE8B;
    transform: rotate(90deg);
    top: 0px
  }
  div:after{
    background:#F7F3D7;
    transform: rotate(-90deg);
    top: 100px;
    left: 0
  }
  
</style>
```