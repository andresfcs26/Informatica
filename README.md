<html>
<body bgcolor="red"> 
<html>


<html>
<head><title>ball html5</title></head>
<body>
 <canvas id="c" width="1000" height="1000"></canvas>
 <script type="text/javascript">
 
 var canvas, ctx;
 
 function drawBall(x,y,r,color){
  ctx.fillStyle = color;
  ctx.beginPath();
  ctx.arc(x, y, r, 0, Math.PI*2, true);
  ctx.closePath();
  ctx.fill();
 }

 function clear(){
  canvas.width =  canvas.width;
 }
 
 function init(){
  canvas = document.getElementById("c");
  ctx = canvas.getContext("2d");
  setInterval(loop, 1000/30);
 }
 
 function loop(){
  clear();

 drawBall(100, 50,20,"#FFFFFF");
 drawBall(150, 50,20,"#FFFFFF");
 drawBall(200, 50,20,"#FFFFFF");
 drawBall(100,100,20,"#FFFFFF");
 drawBall(150,100,20,"#FFFFFF");
 drawBall(200,100,20,"#000000");
 drawBall(100,150,20,"#FFFFFF");  
 drawBall(150,150,20,"#000000");
 drawBall(200,150,20,"#FFFFFF");
 drawBall(100,200,20,"#FFFFFF");
 drawBall(150,200,20,"#000000");
 drawBall(200,200,20,"#000000");
 drawBall(100,250,20,"#000000");
 drawBall(150,250,20,"#FFFFFF");
 drawBall(200,250,20,"#FFFFFF");
 drawBall(100,300,20,"#000000");
 drawBall(150,300,20,"#FFFFFF");
 drawBall(200,300,20,"#000000");
 drawBall(100,350,20,"#000000");
 drawBall(150,350,20,"#000000");
 drawBall(200,350,20,"#FFFFFF");
 drawBall(100,400,20,"#000000");
 drawBall(150,400,20,"#000000");
 drawBall(200,400,20,"#000000");

 }
 
 window.onload = init;
  
 </script>
</body>
</html>
