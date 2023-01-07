```html
<div></div>

<style>
  *{
    background:#007065;
  }
  div {
    width:0px;
    border-bottom:100px solid #00A79D;
    border-left:125px solid transparent;
    border-right:125px solid transparent;
    position:absolute;
    bottom:50px;
    left:50%;
    transform:translatex(-50%);
  }
  div:before,div:after{
    content:'';
    border-left:125px solid transparent;
    border-right:125px solid transparent;
    width:0px;
    position:absolute;
    left:50%;
    transform:translatex(-50%);
  }
  div:before{
    border-bottom:100px solid #F5C181;
    top:-50px;
  }
  div:after{
    border-bottom:100px solid #FFEECF;
    top:-100px;
  }
</style>
```