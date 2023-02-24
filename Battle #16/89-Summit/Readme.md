```html
<div id="a"></div>
<div id="b"></div>

<style>
  body{
    background:#191919;
  }
  #a{
    width: 200px;
    height: 200px;
    background:#F9E492;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
  }
  #b{
    width: 200px;
    height: 200px;
    background: radial-gradient(circle at -6px -6px, #191919 100px, #4F77FF 1% );
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,25%) rotate(45deg);
  }
</style>
```