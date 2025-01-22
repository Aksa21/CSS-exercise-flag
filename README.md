# CSS-exercise-flag
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Flag Project</title>
  <style>
    /* Write your CSS Code here */
    .flag{
      height: 600px;
      width:900px;

      background-color:red;
      border:6px solid white;
    }
    .flag>p{
      color: white;
      font-family:'Times New Roman', Times, serif;
      font-size: xx-large;
      position: relative;
      left: 380px;
      top: 40px;
    }

    .flag>div{
      height: 200px;
      width:900px;
      background-color: blue;
      position:relative;
      top:110px;
    }
    #circle{
      height: 200px;
      width: 200px;
      border-radius: 50%;
      background-color: white;
      position: absolute;
      left:350px;
    }
    #circle>p{
      color: black;
      font-family:'Times New Roman', Times, serif;
      font-size:xx-large;
      position: relative;
      left: 60px;
      top: 60px;
    }
    

    
  </style>
</head>


<body>
  <div class="flag">
    <p>The Flag</p>
    <div>
      <div id="circle">
        <p>of Laos</p>
      </div>
    </div>
  </div>
</body>

</html>
