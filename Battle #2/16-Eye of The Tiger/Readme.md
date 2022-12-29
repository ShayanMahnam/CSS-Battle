```html
<div class="c1"></div>
<div class="triangle l"></div>
<div class="triangle r"></div>
<div class="c2"></div>
<style>
  body{
    background:#0B2429;
  }
  .c1 {
    width: 200px;
    height: 200px;
    background: #998235;
    border-radius:50%;
    position: absolute;
    left: 100px;
    top:50px;
  }
  .c2{
    width: 50px;
    height: 50px;
    background: #0B2429;
    border-radius:50%;
    position: absolute;
    left: 130px;
    top:80px;
    border:45px solid #F3AC3C;
    outline: 20px solid #0B2429;
  }
  
  .triangle{
    position: absolute;
    border-top: 80px solid #998235;
    border-left: 80px solid transparent;
    border-right: 80px solid transparent;
    
  }
  .l{
    transform: rotate(90deg);
    top: 110px;
    left: 20px;
  }
  .r{
    transform: rotate(-90deg);
    top: 110px;
    right: 20px;
  }
</style>
```