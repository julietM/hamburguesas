
<html>
    <head>
        <title>hamburguesas</title>
    </head>
    <style>
  .pan{
  width: 400px;
  height: 40px;
  border-top-left-radius:100px;
  border-top-right-radius:100px;
  background:#FFA000;
  margin-left:auto;
  margin-right:auto;
}
.pollo{
  width: 350px;
  height: 30px;
  border-radius:5px;
  background:#B71C1C;
  margin-left:auto;
  margin-right:auto;
}
.carne{
  width: 350px;
  height: 20px;
  border-radius:6px;
  background:#E91E63;
  margin-left:auto;
  margin-right:auto;  
 
}
.vegetal{
  width: 350px;
  height: 20px;
  border-radius:6px;
  background:green;
  margin-left:auto;
  margin-right:auto;
}
.pan1{
   width: 400px;
  height: 40px;
  border-bottom-left-radius:100px;
  border-bottom-right-radius:100px;
  background:#FFA000;
  margin-left:auto;
  margin-right:auto;
}
p{
  font-size:60px;
  text-align:center;
  font-family:Matura MT Script Capitals;
}
.pan{
   animation: anim1 1s forwards;
}
.pollo{
    animation: anim1 1s 1s forwards;
}
.carne{
    animation: anim1 1s 2s forwards;
}
.vegetal{
    animation: anim1 1s 3s forwards;
}
.pan1{
    animation: anim1 1s 4s forwards;
}
  
@keyframes anim1{ 
  0%{
    opacity:0;
    transform:translateX(-200px)
  }
  
  80% {
    transform: rotate(0)
  }
  90%{
    transform: rotate(-10deg)
  }
  
  95%{
    transform: rotate(10deg)
  }
  
  100%{
    opacity:1;
    transform:rotate(0) translateX(0)
  }

    </style>
    <body>
        <div class="pan"></div>
        <div class="pollo"></div>
        <div class="carne"></div>
        <div class="vegetal"></div>
        <div class="pan1"></div>
        
        <p>hamburguesas</p>
    </body>
</html>
