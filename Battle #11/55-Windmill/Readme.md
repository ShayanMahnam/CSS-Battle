```html
<div id="a"></div>
<div id="b"></div>

<style>
  *{background:#191919}
  #a,#a:after {
    width: 100px;
    height: 50px;
    background: #4F77FF;
    border-radius:50px 50px 0 0;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-25%,-150%) rotate(90deg)
  }
  #a:after{
    content:'';
    transform:translate(50%,50%) rotate(180deg)
  }
  #b,#b:after {
    width: 100px;
    height: 50px;
    background: #F9E492;
    border-radius:50px 50px 0 0;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-100%,-100%)
  }
  #b:after{
    content:'';
    transform:translate(50%,50%) rotate(180deg)
  }
</style>
```