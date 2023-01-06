```html
<style>
  body:before,
  body:after{
    content:'';
    width: 50px;
    height: 200px;
    background: #A3A368;
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-50%, -50%) rotate(45deg);
    mix-blend-mode: screen;
  }
  body:after{
    background:#F3AC3C;
    transform: translate(-50%, -50%) rotate(-45deg);
  }
</style>

```