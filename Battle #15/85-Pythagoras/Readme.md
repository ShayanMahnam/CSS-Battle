```html
<div></div>

<style>
  body{
    background:#D25B70
  }
  div, div:before, div:after {
    width: 100px;
    height: 100px;
    background: #F7F3DA;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,0%)
  }
  div:after{
    content:'';
    width: 60px;
    height: 60px;
    background:#6CB3A9;
    transform:translate(-144%,-204%) rotate(37deg)
  }
div:before{
  content:'';
    width: 80px;
    height: 80px;
    background:#F6DF96;
    transform:translate(2%,-185%) rotate(37deg)
}
  
</style>
```