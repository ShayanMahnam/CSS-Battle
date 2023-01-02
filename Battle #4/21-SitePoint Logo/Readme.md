### My solution 
```html
<div id="o"></div>
<div id="b"></div>
<style>
  *{
    background:#222;
  }
  *:before{
    content:'';
    position: absolute;
  }
  #o, #o:before {
    width: 30px;
    height: 100px;
    background: #F2994A;
    rotate: 45deg;
    position: absolute;
    left: 155px;
    top: 57px;
    border-radius: 0 0 0 10px;
  }
  #o:before{
    width: 30px;
    height: 70px;
    top:50px;
    left:30px;
    rotate:-90deg;
    border-radius: 10px 0 5px 0;
  }
  #b, #b:before {
    width: 30px;
    height: 100px;
    background: #2D9CDB;
    rotate: -135deg;
    position: absolute;
    left: 213px;
    top: 140px;
    border-radius: 0 0 0 10px;
  }
  #b:before{
    width: 30px;
    height: 70px;
    top:50px;
    left:30px;
    rotate:-90deg;
    border-radius: 10px 0 5px 0;
  }
</style>
```

### Other Solution

```html
<div class="container">
  <div class="bar orange"></div>
  <div class="bar blue"></div>
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
    background: #222;
    position: relative;
  }
  .bar {
    position: absolute;
    width: 100px;
    height: 80px;
    background: transparent;
    top: 50%;
    left: 50%;
    border-top-left-radius: 10px;
    border-bottom-right-radius: 5px;
  }
  .orange {
    transform: translate(-62px, -64px) rotate(-45deg);
    border-left: 30px solid #F2994A;
    border-top: 30px solid #F2994A;
  }
  .blue {
    transform: translate(-40px, -16px) rotate(135deg);
    border-left: 30px solid #2D9CDB;
    border-top: 30px solid #2D9CDB;
  }
</style>
```