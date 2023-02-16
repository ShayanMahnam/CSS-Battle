```html
<div id="a"></div>
<div id="b"></div>
<div id="c"></div>
<div id="d"></div>
<div id="e"></div>
<div id="f"></div>
<div id="g"></div>
<div id="h"></div>
<div id="i"></div>
<div id="j"></div>
<style>
  *{
    box-sizing:border-box;
  }
  body{
    background:#191919;
  }
 #a {
    width: 20px;
    height: 150px;
    border:5px solid #E08027;
    border-top:none;
    border-bottom:none;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-425%,-50%);
    filter: drop-shadow(-50px 0px 0 #E08027) drop-shadow(50px 0px 0 #E08027);
  }
  #f{
    width: 20px;
    height: 50px;
    border:5px solid #E08027;
    border-top:none;
    border-bottom:none;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-925%,-150%);
    filter: drop-shadow(200px 100px 0 #E08027)
  }
  #b {
    width: 70px;
    height: 40px;
    border:5px solid #E08027;
    border-bottom:none;
    border-radius:50px 50px 0 0;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-121.6%,-275%);
    filter: drop-shadow(-100px 0px 0 #E08027);
  }
  #c{
    width: 70px;
    height: 40px;
    border:5px solid #E08027;
    border-top:none;
    border-radius:0 0 50px 50px;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-193%,175%);
    filter: drop-shadow(100px 0px 0 #E08027) drop-shadow(-200px -100px 0 #E08027);
  }

  #d{
    width: 40px;
    height: 25px;
    border:5px solid #E08027;
    border-top:none;
    border-radius:0 0 50px 50px;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-50%,280%);
    filter: drop-shadow(-100px 0px 0 #E08027) drop-shadow(-200px -100px 0 #E08027);
  }
  #e{
    width: 40px;
    height: 25px;
    border:5px solid #E08027;
    border-bottom:none;
    border-radius:50px 50px 0 0;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(-175%,-380%);
    filter: drop-shadow(-100px 0px 0 #E08027);
  }

  #g{
    width: 55px;
    height: 36px;
    border:5px solid #E08027;
    border-bottom:none;
    border-right:none;
    border-radius:50px 0 0 0;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(27%,-30%);
  }
  #h{
    width: 45px;
    height: 25px;
    border:5px solid #E08027;
    border-bottom:none;
    border-right:none;
    border-radius:20px 0 0 0;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(66%,20%);
  }
  #i{
    width:50px;
    height:30px;
    background:#E08027;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(130%,-50%);
    border-radius:30px 50px 50px 30px;
  }

  #j{
    width:10px;
    height:10px;
    background:#191919;
    position:absolute;
    left:50%;
    top:50%;
    transform:translate(950%,-130%);
    border-radius:50%;
    box-shadow: 0 16px #191919;
  }
</style>

```