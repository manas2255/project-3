<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Princess 's Birthday</title>
    <style>
        body{
background: linear-gradient(to bottom, #ffe4ec, #ffd6e0);
color: #4a0e2a;
}
.box{
position: absolute;
top: 40%;
left: 50%;
transform: translate(-50%,-50%);
background-color: lightpink;
width: 200px;
height: 100px;
border: 5px dashed white;
font-size: 25px;
padding-left: 20px;
border-radius: 15px;
}
.text{
position: absolute;
  opacity: 0;
}
.text:nth-child(1){
  animation: show 4s forwards;
  animation-delay: 2s;
}
.text:nth-child(2){
  animation: show 4s forwards;
  animation-delay: 6s;
}
.text:nth-child(3){
  animation:show 4s forwards;
  animation-delay: 10s;
}
.text:nth-child(4){
  animation : last 4s forwards;
  animation-delay: 14s;
}
@keyframes show{
  0%{opacity: 0;}
  1%{opacity: 1;}
  80%{opacity: 1;}
  100%{opacity:0;}
}
@keyframes last{
  0%{opacity: 0;}
  1%{opacity:1;}
  100%{opacity:1;}
}
    </style>
</head>
<body>
    <div class="box">
     <h2 class="text">
        Hey....
     </h2>
     <h2 class="text">
      hello...
     </h2>
     <h2 class="text">
       hii..
     </h2>
     <h2 class="text">
        byee
     </h2>
    </div>
</body>
</html>
