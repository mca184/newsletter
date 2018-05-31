---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<html>
<style>
body{
background: linear-gradient(to right, rgba(255,100,0,0), rgba(255,100,0,8));
}
.photobanner {
 height: 233px;
 width: 3550px;
 margin-bottom: 80px;
}

 
.photobanner img {
 -webkit-transition: all 0.5s ease;
 -moz-transition: all 0.5s ease;
 -o-transition: all 0.5s ease;
 -ms-transition: all 0.5s ease;
 transition: all 0.5s ease;
}
 
.photobanner img:hover {
 -webkit-transform: scale(1.1);
 -moz-transform: scale(1.1);
 -o-transform: scale(1.1);
 -ms-transform: scale(1.1);
 transform: scale(1.1);
 cursor: pointer;
 
 -webkit-box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
 -moz-box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
 box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
}
.first {
 -webkit-animation: bannermove 30s linear infinite;
    -moz-animation: bannermove 30s linear infinite;
     -ms-animation: bannermove 30s linear infinite;
      -o-animation: bannermove 30s linear infinite;
         animation: bannermove 30s linear infinite;
}
 
@keyframes "bannermove" {
 0% {
    margin-left: 0px;
 }
 100% {
    margin-left: -2125px;
 }
 
}
 
@-moz-keyframes bannermove {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
 
@-webkit-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
 
@-ms-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
 
@-o-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
</style>
<body>
<div class="photobanner">
<img class="first" src="a13.jpg" alt="" style="max-width:350px;"/>
<img src="a12.jpg" alt="" style="max-width:800px;"/>
    	<img src="about8.jpg" alt="" style="max-width:400px;"/>
    	<img src="about.jpeg" alt="" style="max-width: 550px;"/>
		<img src="a2.png" alt="" style="max-width: 530px;"/>
    	</div>
</body>
</html>
