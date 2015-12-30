---
layout: default
body-class: wider
---

hello

<div class="wider midnight">
		
			
				
					{% for post in site.categories.blog limit:5 %}
					 <a href="{{site.baseurl}}/{{post.url}} ">
					 	<div class="workWide" style="background-image:url('{{post.featureImg}}');">
					 		<div class="wideOverlay blackBg09">
							 	<div class="grid">
							 			<div class="unit whole">
											<span class="counter fLeft">{{ counter }}</span>
											<span class="title block">{{post.title}}</span>
											<span class="subtitle block">{{post.subTitle}}</span>
							 			</div>	
								</div>
							</div>	
						</div>
					</a>
					{% endfor %}

			
		 
</div>	
<!--
		<div class="grid">
			<ul class="recentWork">
				<li>Selected work 2010-2015</li>
				{% for post in site.categories.work limit:5 %}
				<li class="block">
					<a class="midnight" href="{{site.baseurl}}/{{post.url}}">
						<span class="title">{{post.title}}</span>
						<span class="subtitle">{{post.subtitle}}</span>
					</a>

				</li>
				{% endfor %}
			</ul>
		 </div>
-->