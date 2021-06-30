<template>
  <div class="header" id="head">	
      <div class="container"> 
         <div class="header-top">
      		 <div class="logo">
				<a href="index.html"><img src="" alt=""/></a>
			 </div>
		   <div class="top-menu">
		    	<span class="menu"> </span>
                <ul>
                    <nav class="cl-effect-5">
                    <li><a class="active" href="index.html"><span data-hover="Home">home</span></a></li>
                    <li><a href="#about" class="scroll"><span data-hover="about">about</span></a></li>
                    <li><a href="#work" class="scroll"><span data-hover="work">work</span></a></li>
                    <li><a href="#services" class="scroll"><span data-hover="services">services</span></a></li>
                    <li><a href="#contact" class="scroll"><span data-hover="contact">contact</span></a></li>
                    </nav>
                </ul>
			 </div>
			 <!--script-nav-->
		 
			<div class="clearfix"></div>
		 </div>  
		  <div class="index-banner">
       	   <div class="wmuSlider example1">
			   <div class="wmuSliderWrapper">
				   <article style="position: absolute; width: 100%; opacity: 0;"> 
				   	<div class="banner-wrap">
				   	       	<div class="banner_center">
				   		 		<h1>Hello world,</h1> 
				   		 		<h2>I'm a <span>frontend web developer</span></h2>
				   		 		<h2>from the Netherlands</h2>
				   		 		</div>
				   		 </div>
					</article>
				   <article style="position: relative; width: 100%; opacity: 1;"> 
				   	   	<div class="banner-wrap">
				   	      <div class="banner_center">
				   		 		
				   		 		<h2> <span>Frontend Web Developer</span></h2>
				   		 		
				   		 		</div>
				   		  </div>
				   </article>
				   <article style="position: absolute; width: 100%; opacity: 0;">
				   	  	<div class="banner-wrap">
				   	       <div class="banner_center">
				   		 		 
				   		 		<h2><span>Hello world</span></h2>
				   		 		
				   		 		</div>
				   		 </div>
					 </article>
				 </div>
				
            </div>
         
			   	           	      
      </div>
	 </div>     
	</div>  
</template>

<script>
		 $("span.menu").click(function(){
		 $(".top-menu ul").slideToggle("slow" , function(){
		 });
		 });
         
         src="js/jquery.wmuSlider.js"
       			$('.example1').wmuSlider();         
   		     
		 </script>