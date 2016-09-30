---
layout: default
featureImg: assets/peaceYo.jpg
Headline: I'm a self-taught designer in London, available for freelance work.
bgcolor: pitchBlackBg
subTitle: <a href="mailto:nique.shjm.woodhouse@gmail.com">nique.shjm.woodhouse@gmail.com</a> +44 0 7948 888 909
---

<div class="wider bigGapBott h100 saturate1 pos5050 greyscale1_saturate1 bgCover" style="background-image:url('{{ page.featureImg}}')">
	<div class="wideOverlay">
		<div class="grid midnight hero1 w100">
			<div class="unit whole textCenter paddingNo">
				<p class="mediumPrint">{{ page.date | date: '%B %d, %Y' }}	</p>		
			</div>
		      <div class="unit whole paddingNo">
		        <h1 class="textCenter">{{ page.Headline }}</h1>
		      </div>
		      <div class="unit whole textCenter paddingNo">
		      	<p class="mediumPrint">{{page.subTitle}}	</p>
		      </div>
		 </div> 
	</div>		 
</div>		


<div class="wider">
 		 

		<div class="grid">		
			<div class="unit whole dBlock largeGapBottom largeGapTop">
				<h2 class="w50 mAuto textCenter ghost">I work with bold brands I believe in.</h2>
			</div>
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_mtv.svg"/>
			</div>
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_spotify.svg"/>
			</div>	
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_vans.svg"/>
			</div>						
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_adidas.svg"/>
			</div>	
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_appearhere.svg"/>
			</div>
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_nick.svg"/>
			</div>	
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_aande.svg"/>
			</div>						
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_paramount.svg"/>
			</div>				
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_remington.svg"/>
			</div>
			<div class="unit one-fifth">
				<img src="assets/logos/Logos_nike.svg"/>
			</div>			


			<div class="unit whole dBlock largeGapBottom largeGapTop">
				<h2 class="w50 mAuto textCenter ghost">I'm passionate .</h2>
			</div>
		      <div class="half mAuto">

			        <p class="mTopNone">
			        	I'm passionate about transforming complex problems into simple &amp; obvious solutions. I can't swim.  
			        </p>
				 	<div class="grid__lock block">	
						<h4 class="grid__title block midnight">{{page.title}}</h4>
						<p class="subtitle block grey">{{page.subtitle}}</p>
					</div>						        
			        <p class="">
			        	 I was the first Creative Director at <a href="http://www.wirewax.com">Wirewax</a>, a video editing platform used by brands like Spotify, NBC Universal, Nike &amp; BBC.  
					</p>
					<p class="">
			        	I'm honored by the high regard we were held by global creative agencies, their clients &amp; the impact my role had on the bottom line - with share value increasing 8x in my 2 years of service.
			        </p>
			        <p class="">
			        	Today I create my own products from my London studio, alongside helping others with theirs around the world.  
			        </p>

				</div>
		</div>		 


		<div class="grid bigGapBott">
		      <div class="unit one-third relative">
		      		<h4 class="absolute NinetyDegTitle"><span class="gold smallGapBott">02</span> Awards</h4>	
		      </div>				

	      <div class="unit two-thirds">
	        <ul class="w80 fRight blockLi list mediumGapBott">
	        	
	        	<li>1x Awwwards Honorable Mention</li>
	        	<li>1x OnePage Most Loved of the Year</li>
	        	<li>1x Linkage Site of the week </li>
	        	<li>1x CSS Design Awards Design of the day</li>
	        	<li>1x IAB Best Digital Creative</li>
	        	<li>1x Mashie</li>
	        </ul>
	      </div>	      	      
	    </div>

	    <div class="grid">
	    	<div class="unit one-third relative">
	    		<h4 class="absolute NinetyDegTitle"><span class="gold smallGapBott">03</span> Studio</h4>	
	    	</div>

	    	<div class=" two-thirds mAuto ">
	    		<img src="http://blog.readymag.com/wp-content/uploads/2014/11/anton-repponen-workplace-11.jpg"/>
	    	</div>	    	

   	
	    </div>

	    <div class="grid">
	    	<div class=" one-third mAuto">
	    		<img src="http://antonandirene.com/upload/contact-photos/1.jpg"/>
	    	</div>
	    	<div class=" one-third mAuto">
	    		<img src="http://antonandirene.com/upload/contact-photos/3.jpg"/>
	    	</div>	   	    	
	    </div>


</div>





<!--
<div class="wider">

		<script type="text/javascript" src="https://raw.githubusercontent.com/stevenschobert/instafeed.js/master/instafeed.min.js"></script>  
  	<script type="text/javascript">
		var feed = new Instafeed({
		  get: 'user',
		  clientId: '467ede5a6b9b48ae8e03f4e2582aeeb3',
		  userId: 13563994,
		  accessToken: '13563994.467ede5.bfe0ac4ed0fa4d9a84b943687922a92d',
		  resolution: 'standard_resolution',
		  limit: 9,
		  after: function () {
		    var images = $("#instafeed").find('a');
		    $.each(images, function(index, image) {
		      var delay = (index * 75) + 'ms';
		      $(image).css('-webkit-animation-delay', delay);
		      $(image).css('-moz-animation-delay', delay);
		      $(image).css('-ms-animation-delay', delay);
		      $(image).css('-o-animation-delay', delay);
		      $(image).css('animation-delay', delay);
		      //$(image).addClass('animated flipInX');
		    });
		  },
		  template: '<a href="{{link}}" target="_blank" class="instagramImg"><img src="{{image}}" /><span class="likes">&hearts; {{likes}}</span></a>'
		});
		feed.run();
		setTimeout(function(){ $('#instafeed a').attr("target","_blank"); }, 1000);
	</script>
				<div id="instafeed" class="wow fadeIn animated" style="visibility: visible; animation-name: fadeIn;">
				<h1 class="intro-heading tCenter">Instagram</h1>
			</div>
</div>





-->
