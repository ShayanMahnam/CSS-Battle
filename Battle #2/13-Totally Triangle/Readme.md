```html
<div></div>
<style>
  body{
    margin: 0;
    background: #0B2429;
  }
  div,div:after{
    width: 140px;
    height: 140px;
    background: #F3AC3C;
    position:absolute;
  }
  div:after{
    content:'';
    background:#0B2429;
    top:20px;
    left:50px;
    transform:rotate(45deg);
    width: 140px;
    height: 200px;
  }
</style>
```