```html
<div id="a">
  <div id="b"></div>
</div>

<style>
  *{background:#293462}
  #a {
    width: 200px;
    height: 200px;
    background: #FFF1C1;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-50%,-50%);
    overflow:hidden;
  }
  #b{
    width: 200px;
    height: 100px;
    background: #FE5F55;
    position:absolute;
    top:50%;
    left:50%;
  transform:translate(-47%,15%) rotate(-45deg);
    box-shadow: -129px -29px #FE5F55;
  }
</style>
```