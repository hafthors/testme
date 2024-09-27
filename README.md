
<html>
 <head>
    <meta charset="utf-8">
     <head><title>Stina H Test training Webstie - Udemy Student</title>
     <style>
  
     }
     table{
        width:100%;
        border:1px solid black;
     }
     dt{
        font-weight:bold;
        font-size: 1.2em;
     }
     section{
        padding:10px;
        border:1px solid black;
        margin:10px;
     }

      </style>
     </head>
     <body> 
   <h1>Stina Hafthors Resume</h1>

   <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExaDdlN2Q5NnJzcTQzZ3JtM3Rva281aGF5NTMweWt5eHVsejJ0ZmVheSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/mBLYrKaZJACmtum22X/giphy.gif" width="300" height="200">
   
   <nav class="navbar">
    <ul>
      <li><a href="#Int">Interests</a></li>
      <li><a href="#Con">Contact</a></li>
    </ul>
   </nav>
<p>
       Welcome to my website, hope you enjoy it.</p>
     <p>My name is Stina Hafthors</p>

     <div class="content">
		<div class="van-gogh"></div>
</div>
<div class="text"></div>

 @import url('https://fonts.googleapis.com/css2?family=Gluten:slnt,wght@-13..13,100..900&display=swap');

body {
	margin: 0;
	padding: 0;
	width: 100vw;
	height: 100vh;
	overflow: hidden;
	display: flex;
	align-items: center;
	justify-content: center;
	background: url(https://cdn.josetxu.com/img/vg-bg.jpg) no-repeat center center;
	background-size: cover;
}

body:before {
	content: "";
	position: absolute;
	width: 100%;
	height: 100%;
	background: #0008;
}

.content {
	width: 67.2vmin;
	height: 76vmin;
	background: url(https://cdn.josetxu.com/img/vg-bg.jpg) no-repeat center center;
	background-size: contain;
	position: relative;
	transform: scale(0.65);
	overflow: hidden;
	border-radius: 3vmin;
	box-shadow: #00000066 0 0.2vmin 0.4vmin, #00000044 0 0.7vmin 1.3vmin -0.3vmin, #00000033 0 -0.3vmin 0 inset;
	border: 1vmin solid #e4ecee;
}

.text {
	font-family: "Gluten", cursive;
	width: 100%;
	text-align: center;
	position: absolute;
	font-size: 9vmin;
	transform: scale(0.65);
	margin-top: 63vmin;
	text-shadow: 0 -0.5vmin 0.2vmin #ffffff, -0.1vmin 0.7vmin 0.3vmin #172c41;
	color: #85a7b1;
}

.text:before {
	content: "VAN GOGH";
	animation: show-text 6s ease 0s 1;
	animation-fill-mode: forwards;
}

@keyframes show-text {
	0%, 20% { content: "VAN GOGH"; }
	21%, 59% { content: "VAN GOGHING"; }
	60%, 100% { content: "VAN GONE"; }
}		

@keyframes show-text-hover {
	0%, 20% { content: "VAN GOGH"; }
	21%, 59% { content: "VAN GOGHING"; }
	60%, 100% { content: "VAN GONE"; }
}

.van-gogh {
	width: 60vmin;
	height: 68vmin;
	background: url(https://cdn.josetxu.com/img/vg-01.png) no-repeat center center;
	background-size: cover;
	position: absolute;
	right: 0;
	bottom: 0;
	animation: move-start 6s ease 0s 1;
	animation-fill-mode: forwards;
	filter: drop-shadow(0 0 0.5vmin #ffffff88);
}

@keyframes move-start {
	5%, 20% { right: 0; }
	0%, 85%, 100%  { right: -100%; }
}

@keyframes move-hover {
	5%, 20% { right: 0; }
	0%, 85%, 100%  { right: -100%; }
}

.content:hover .van-gogh {
	animation-name: move-hover;
}

.content:hover + .text::before {
	animation-name: show-text-hover;
}
<section class="Exp">
    <h2>Experinece</h2>
    <table>
        <colgroup>
        <col span="1" style="background-color: #dddd;">
    
        </colgroup>
     <tr><th>Company</th>
      <th>Details</th>
      <th>Years</th>
    </tr>
    <tr>
        <td>BOSCH</td>
        <td>Tourist Service</td>
        <td>2020-2024</td>
    </tr>
    <tr>
        <td>GETYOURGUIDE</td>
        <td>Tourist Service</td>
        <td>2015-2020</td>
    </tr>
    <tr>
        <td>Car2go</td>
        <td>CustomerService</td>
        <td>2014-2015</td>
    </tr>
    </table>

<section id="Con">
 <h2>Contact me</h2>
 <p>
    Contact me at my email <a
    href="mailto: s.hafthors@gmail.com">My Email Address</a>
 </p>
</section>

<footer class="footer">Copyright (c) 2022 Stina Hafthors Content please Contact
    me to find out more.</footer>
</footer>

</body>
</html>
