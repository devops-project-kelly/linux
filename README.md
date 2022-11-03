# linux
commands 

<!DOCTYPE html>
<html>
<head>
<title>Basic html tags</title>
<style>
*{
margin:0px auto;
}
body{
background-image:url('images/corporate.jpg');
background-size:cover;
}
.maincontainer{
width:500px;
height:auto;
background-color:rgba(0,0,0,0.6);
margin-top:75px;
/*border:2px solid #000000;*/
padding:50px;
box-sizing:border-box;
margin-bottom:75px;
box-shadow:2px 2px 5px black,-2px -2px 5px black;
transition:0.6s;
}
.maincontainer:hover{
transform:scale(1.02);
box-shadow:10px 10px 5px black,-10px -10px 5px black;
}
.maincontainer p{
color:white;
text-align:justify;
margin:10px;
font-size:18px;
letter-spacing:2px;
text-shadow:2px 2px black;
}
.circle{
width:200px;
height:200px;
border-radius:50%;
float:left;
margin:20px;
shape-outside: circle();
}
.circle img{
width:200px;
height:200px;
border-radius:50%;
}
</style>
</head>
<body>
<div class="maincontainer">
	<div class="circle">
		<img src="bmw.png" >
	</div>
	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. </p>
</div>

</body>
</html>

