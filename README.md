# resume.io
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Front page</title>
  </head>
<style>
  body{
    background-image:url('image2.jpg');
    width:100vw;
    height:100vh;
    background-size: cover;
    background-repeat: no-repeat;
    font-family:italic;
  }
  .text{
    color: black;
    font-family: italic;
    text-align: center;
    justify-content: center;
    padding-top:50px;
    white-space: nowrap;
    
  }
  .box {
    display: flex;
    font-family: italic;
    justify-content: center;
    align-items: center;
    border: none;       
}
.button{
  background-color: black;
  border: none;
  padding: 10px;
  font-family: italic;
  border-radius: 0px;
  cursor: pointer;
  background-color: white;
  color: rgb(151, 118, 189);
  font-weight: bold;  
}
.button:hover{
  opacity: 0.5;
  background-color: black;
}
</style>
<body>
  <div class="text">
    <h1
        style="color:rgb(16, 88, 129);" > Lavanya.S resume
    </h1>  
    <p><i style="font-size:21px;color:rgb(15, 15, 15);"> click the button below to view my resume</i></p>
    
  </div>

  <div  class="box">
    <a href="resume.html">
      <button class="button">
        click here
      </button>
    </a>
  </div>
</body>
</html>
