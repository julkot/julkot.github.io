<!DOCTYPE html>
<html>
<head>
	<title>Homework</title>
	<meta charset="utf-8">
	<style type="text/css">
	.flex-container {
  display: flex; /*inline-flex*/
  flex-direction: column;
  align-items: center;
  background-color: #EAEDED;
  font-size: 25px;
	}
	.white_color {
  color: #FFFFFF;
  font-size: 35px;
  text-align: center;
}
    .white_style {
    	color: #FFFFFF;
       font-size: 25px;
       text-decoration: underline;
       text-align: center;
    }
    .blue_style {
    	color: #21618C;
    	font-size: 25px;
    	text-align: left;
    }
		#id1 {
			width: 99%;
			height: 50px;
			background-color: #2E4053;
			margin-top: 5px;
			border: 0px;
		}
		#id2 {
			width: 99%;
			height: 500px;
			background-color: #FFFFFF;
			margin: 2px
		}
		
		.column {
    float: left;
}

.left {
    width: 25%;
    height: 500px; 
}

.right {
    width: 75%;
    height: 500px;
}
#grad1 {
    height: 500px;
    background: #515A5A; 
    background: linear-gradient(to right, #515A5A , #B2BABB);
}
a:link {
    color: #FFFFFF; 
    background-color: transparent; 
    text-decoration: none;
}
a:hover {
    color: blue;
    background-color: transparent;
    text-decoration: underline;
}
.label {
    color: white;
    padding: 5px;
    font-size: 20px;
    text-align: center;
}
.L1 {background-color: #4CAF50;} 
.L2 {background-color: #2196F3;} 
.L3 {background-color: #ff9800;} 
<meta name="viewport" content="width=device-width, initial-scale=1">

	</style>
</head>
		<body>
			<div class="flex-container">
				<div id="id1" class="white_color"> Curriculum Vitae</div>
				<div id="id2" class="row">
  <div id="grad1" class="column left" style="background-color:#515A5A;">
  
  <img src="https://julkot.github.io/IMG_3995.JPG" alt="Avatar" style="width:25%; border-radius: 50%;  display: block;
    margin: auto;">
    <h2 class="white_color">Кот Юлия</h2>
    <p class="white_style"> Люблю:</p>
    <span class="label L1">Петь</span>
<span class="label L2">Рисовать</span>
<span class="label L3">Танцевать</span>
    <p class="white_style" > Контакты:</p>
    <ul>
    <li> <a href="https://www.facebook.com/profile.php?id=100017861023493" target="_blank">Facebook</a> </li>
    <li> <a href="https://www.linkedin.com" target="_blank">Linkedin</a></li>
</ul>
  </div>
  <div class="column right" style="background-color:#FFFFFF; border-left: 2px">
    <p class="blue_style"> <b>Дата Рождения</b></p>
    <p class="blue_style">3 октября</p>
        <hr noshade size="4" width="200px" align="left">
    <p class="blue_style"> <b>Место Рождения</b></p>
    <p class="blue_style">г.Донецк</p>
    <hr noshade size="4" width="200px" align="left">
    <p class="blue_style"> <b>Soft Skills</b></p>
    <ul class="blue_style" type="circle"> 
    	<li>Photoshop</li>
    	<li>Excel</li>
    	<li>Paint</li>
    </ul>
	</div>
     </div>
  </body>			
</html>
