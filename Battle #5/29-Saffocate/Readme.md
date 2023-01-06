### My Solution

```html
<div id="a"></div>
<div id="b"></div>

<style>
  *{
    background:#F3AC3C;
  }
  #a {
    width: 150px;
    height: 150px;
    background: #1A4341;
    position:absolute;
    top:70px;
    left:120px;
    rotate:45deg;
  }
  #b {
    width: 200px;
    height: 200px;
    background: #F3AC3C;
    position:absolute;
    border-radius:50%;
    top:-65px;
    left:0px;
    box-shadow: 180px 0px #F3AC3C,180px 180px #F3AC3C,-10px 185px #F3AC3C;
  }
</style>
```
### Other Solution

```html
<div class="container">
  <div class="transparent-square">
    <div class="circle top-left"></div>
    <div class="circle top-right"></div>
    <div class="circle bottom-left"></div>
    <div class="circle bottom-right"></div>
  </div>
</div>

<style>
  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  .circle {
    width: 200px;
    height: 200px;
    border-radius: 50%;
  }
  .container {
    background: #f3ac3c;
    width: 100vw;
    height: 100vh;
    position: relative;
  }
  .transparent-square {
    width: 200px;
    height: 200px;
    background: #1a4341;
    position: relative;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    overflow: hidden;
  }
  .top-left,
  .top-right,
  .bottom-left,
  .bottom-right {
    background: #f3ac3c;
    position: absolute;
  }
  .top-left {
    transform: translate(-50%, -50%);
  }
  .top-right {
    transform: translate(50%, -50%);
  }
  .bottom-left {
    transform: translate(-50%, 50%);
  }
  .bottom-right {
    transform: translate(50%, 50%);
  }
</style>
```