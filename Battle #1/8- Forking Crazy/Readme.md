<div></div>
<style>
  body {
    background: #6592CF;
  }

  *::after, *::before {
    position: fixed;
    content: '';
    background: #060F55;
  }

   div {
    margin: 110px 122px;
    width: 140px;
    height: 140px;
    background: #060F55;
    border-radius: 0 0 50% 50%;
  }

    div::after {
    color: #060F55;
    margin: -60px 0;
    width: 20px; 
    height: 110px; 
    border-radius: 30px 30px 30px 30px;
     box-shadow: 
      20px 0 #6592CF,
      40px 0,
      60px 0 #6592CF,
      80px 0,
      100px 0 #6592CF,
      120px 0; 
  }

  div::before {
    margin: 130px 60px;
    width: 20px; 
    height: 70px;
  }
</style>