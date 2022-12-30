### My Solution
```html
<div id="r"></div>
<div id="c1"></div>
<div id="c2"></div>
<div id="c3"></div>
<style>
  *{background:#62306D}
  #r, #r::before {
    width: 140px;
    height: 100px;
    background: #F7EC7D;
    position:absolute;
    top:100px;
    left:100px;
  }
  #r::before{
    content:'';
    width:60px;
    top:0px;
    left:140px;
    background:#E38F66;
  }
  #c1, #c1::before{
    width:40px;
    height:40px;
    background:#62306D;
    border-radius:100%;
    position:absolute;
    top:80px;
    left:80px;
  }
  #c1::before{
    content:'';
    left:0;
    top:100px
  }
  #c2, #c2::before{
    width:40px;
    height:40px;
    background:#62306D;
    border-radius:100%;
    position:absolute;
    top:80px;
    right:80px;
  }
  #c2::before{
    content:'';
    left:0;
    top:100px
  }
  #c3, #c3::before{
    width:20px;
    height:20px;
    background:#62306D;
    border-radius:100%;
    position:absolute;
    top:90px;
    right:150px;
  }
  #c3::before{
    content:'';
    left:0;
    top:100px
  }
</style>
```

### Other Solution

```html
<div class="container">
  <div class="ticket-transparent">
    <div class="round-dot lg top-left"></div>
    <div class="round-dot lg bottom-left"></div>
    <div class="round-dot sm top-center"></div>
    <div class="round-dot sm bottom-center"></div>
    <div class="round-dot lg top-right"></div>
    <div class="round-dot lg bottom-right"></div>
    <div class="ticket">
      <div class="yellow-side"></div>
      <div class="orange-side"></div>
    </div>
  </div>
</div>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .container {
    width: 100vw;
    height: 100vh;
    background: #62306d;
    position: relative;
  }
  .ticket,
  .ticket-transparent {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 200px;
    height: 100px;
  }
  .ticket {
    display: flex;
  }
  .yellow-side {
    width: 70%;
    background: #f7ec7d;
  }
  .orange-side {
    width: 30%;
    background: #e38f66;
  }
  .round-dot {
    position: absolute;
    z-index: 10;
    background: #62306d;
    border-radius: 50%;
  }
  .lg {
    width: 40px;
    height: 40px;
  }
  .sm {
    width: 20px;
    height: 20px;
  }
  .top-left {
    transform: translate(-20px, -20px);
  }
  .bottom-left {
    bottom: 0;
    left: 0;
    transform: translate(-20px, 20px);
  }
  .top-center {
    top: 0;
    left: 70%;
    transform: translate(-10px, -10px);
  }
  .bottom-center {
    bottom: 0;
    left: 70%;
    transform: translate(-10px, 10px);
  }
  .top-right {
    right: 0;
    transform: translate(20px, -20px);
  }
  .bottom-right {
    bottom: 0;
    right: 0;
    transform: translate(20px, 20px);
  }
</style>
```