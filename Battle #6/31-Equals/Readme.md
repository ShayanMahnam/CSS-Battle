```html
<div></div>

<style>
  *{
    background:#AA445F;
  }
  div,div:before {
    width: 200px;
    height: 100px;
    background: #E38F66;
    position:absolute;
    border-radius:100px 100px 0 0;
    rotate:90deg;
    right: 25px;
    top:100px;
  }
  div:before{
    content:'';
    rotate:-180deg;
    top:150px;
    right:0;
    background:#F7EC7D;
  }
</style>
```