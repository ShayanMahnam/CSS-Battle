```html
<div></div>

<style>
  *{
    background:#6592CF;
  }
  div, div:before, div:after {
    position: absolute;
    width: 80px;
    height: 40px;
    border: 20px solid #060F55;
    border-top-left-radius: 100px;
    border-top-right-radius: 100px;
    border-bottom: 0;
    top: 40px;
    left: 40px;
  }
  div:before{
    content:'';
    top: -20px;
    left: 180px;
  }
  div:after{
    content:'';
    top: 140px;
    left: 80px;
    rotate:180deg;
  }
</style>
```