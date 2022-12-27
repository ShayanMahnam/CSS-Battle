### My Solution

<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<style>
  body{
    background: #62306D
  }
  div {
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    position: absolute;
    border-radius: 0 0 50px 50px;
  }
  #a {
    top: 50px;
    left: 150px;
    transform: rotate(180deg);
  }
  #b {
    top: 150px;
    left: 50px;
  }
  #c {
    top: 150px;
    left: 250px;
  }
</style>

### Other Solution

<div></div>
<style>
  body {
    background: #62306D;
  }
  div, div::before, div::after {
    margin: 42px 142px;
    width: 100px;
    height: 100px;
    background: #F7EC7D;
    display: inline-block;
    border-radius: 50px 50px 0 0;
  }
  div::before, div::after {
    content: "";
    border-radius: 0 0 50px 50px;
    margin: 100px -100px;
  }
  div::after {
    margin: -200px 100px;
  }
</style>
