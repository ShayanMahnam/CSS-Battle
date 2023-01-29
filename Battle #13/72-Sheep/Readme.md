```html
<div class="container">
      <div class="body">
        <img />
        <img />
        <img />
        <img />
        <img />
        <u>
          <img />
          <img />
        </u>
        <img />
        <img />
        <img />
      </div>
    </div>
    
<style>
  body {
  background-color: #243D83;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  margin-left: 24px;
}

.container {
  background-color: white;
  width: 400px;
  height: 300px;
  position: relative;
  overflow: hidden;
}

.body {
  margin: 0;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  position: relative;
}

.container * {
  background: #243d83;
  position: absolute;
}
.container img {
  margin: 57px 162px;
  background: #6592cf;
  padding: 25px 30px;
  border-radius: 50%;
  transform-origin: 30px 85px;
  transform: rotate(calc(var(--r, 2) * 45deg)) var(--i, scale(1));
}
.container img:nth-of-type(2n) {
  --i: translateY(3.5px);
}
.container img:nth-child(2) {
  --r: 3;
}
.container img:nth-child(3) {
  --r: 4;
}
.container img:nth-child(4) {
  --r: 5;
}
.container img:nth-child(5) {
  --r: 6;
}
.container img:nth-child(7) {
  --r: 7;
}
.container img:nth-child(8) {
  --r: 8;
}
.container img:nth-child(9) {
  --r: 9;
}
.container u {
  margin: 72px 147px;
  padding: 40px 30px;
  border-radius: 50px;
  border: 15px solid#6592CF;
}
.container u img {
  padding: 5px;
  margin: 0;
  transform: none;
  top: 35px;
  left: 15px;
}
.container u img + img {
  left: 35px;
}
</style>
```