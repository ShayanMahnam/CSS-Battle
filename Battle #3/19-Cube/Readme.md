```html
<div class="diag-square"></div>
<div class="rect skew-left"></div>
<div class="rect skew-right"></div>

<style>
  *{background:#0B2429}
  .diag-square {
    position: absolute;
    width: 100px;
    height: 100px;
    background: #F3AC3C;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -15%) rotate(45deg) 
  }
  .rect {
    position: absolute;
    width: 70px;
    height: 70px;
    top: 50%;
    left: 50%;
  }
  .skew-left {
    background: #1A4341;
    transform: translate(0px, -70px) skew(0deg, 45deg);
  }
  .skew-right {
    background: #998235;
    transform: translate(-70px, -70px) skew(0deg, -45deg) ;
  }
</style>
```