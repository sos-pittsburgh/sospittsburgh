---
title: Save Our Symphony Pittsburgh
layout: default
---

<a name="mission" />

<section class="box special" >
	<header class="major">
		<h2>Our Mission
		</h2>
		<p>
			The mission of Save Our Symphony Pittsburgh
			is to promote and support the world-class excellence and stature
			of the Pittsburgh Symphony Orchestra and to ensure its preservation
			in our community for future generations.
		</p>
		
		<ul class="actions">
			<li><a href="/mission" class="button alt">Learn More</a></li>
		</ul>
	</header>
	
</section>


<a name="rescuerecitals" />
				
<div class="row">
<div class="12u">
	<header class="major">
		<h2>Rescue Recitals and Upcoming Events
		</h2>
	</header>
</div>

{% for post in site.categories.events offset: 0 limit: 3 %}
	<div class="4u">
	<section class="box special rescue-recital">
		<!-- <span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span> -->
		<h4><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h4>
		<span class="date">{{ post.date | date_to_string }}</span>
		<p>{{ post.description }}</p>
		<ul class="actions">
			<li><a href="{{ site.baseurl }}{{ post.url }}" class="button alt">View</a></li>
		</ul>
	</section>
  </div>
{% endfor %} 


</div>


<a name="get-involved" />

<section class="box special features">
	<header class="major">
		<h2>Get Involved
		</h2>
		<p>
			Four things you can do to ensure the future of the Pittsburgh Symphony
		</p>
	</header>
	<div class="features-row">
		<section>
			<h3>1. Attend Concerts</h3>
			<p>First and formost, buy an <a href="https://pittsburghsymphony.org/pso_home/web/tickets-landing">annual subscription</a> to the PSO, attend concerts often and if you can, donate to the PSO's <a href="https://pittsburghsymphony.org/pso_home/web/give-landing" target="_blank">annual fund</a></p>
		</section>
		<section>
			<h3>2. Host a Rescue Recital</h3>
			<p>Attend or host an SOS Pittsburgh Rescue Recital; an in-home concert where you get to experience world class music up close. <a href="/rescuerecitals">Learn more</a></p>
		</section>
	</div>
	<div class="features-row">
		<section>
			<h3>3. Support us</h3>
			<p>Donate to SOS as we build a fund for musicians at the Pittsburgh Foundation. <a href="#">Learn more</a></p>
		</section>
		<section>
			<h3>4. Spread the Music</h3>
			<p>Bring a friend and introduce them to the music of the PSO.</p>
		</section>
	</div>
</section>

<a name="board" />


<section class="box special">
	<header class="major">
		<h2>Our Board
		</h2>
		<p>
			We're made up of PSO patrons, audience advocates, listeners, donors, subscribers, business owners, community members and students. The one thing we have in common: our passion for this great orchestra, and our desire to see it remain a thriving and vital part of the fabric of our great city.
		</p>
		
		</header>
		
		
		<div class="row">
			<div class="4u">

				<section class="box special">
					<!--<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>-->
					<h3>Alice Gelormino</h3>
					<p>Treasurer</p>
				</section>

			</div>
			<div class="4u">

				<section class="box special">
					<!--<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>-->
					<h3>Geoffrey McGovern</h3>
					<p> Vice Chair</p>
				</section>

			</div>
		
			<div class="4u">

				<section class="box special">
					<!--<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>-->
					<h3>Kathy Maskalick</h3>
					<p>Treasurer</p>
				</section>

			</div>
			
			<div class="4u">

				<section class="box special">
					<!--<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>-->
					<h3>David Maskalick</h3>
					<p>Secretary</p>
				</section>

			</div>
			<div class="4u">

				<section class="box special">
					<!--<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>-->
					<h3>Gillian Cannell</h3>
					<p> &nbsp; </p>
				</section>

			</div>
		
			<div class="4u">

				<section class="box special">
					<!--<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>-->
					<h3>Connie Phillips</h3>
					<p> &nbsp; </p>
				</section>

			</div>
			
			
		</div>

		<ul class="actions">
			<li><a href="/mission#leadership" class="button alt">Learn More</a></li>
		</ul>
		
	
</section>

<a name="news" />
		
		
<!-- <div class="row">
	<div class="12u">
		<header class="major">
			<h2>What we're up to
			</h2>
		</header>
	</div>

	<div class="4u">

		<section class="box special">
			<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
			<h3>News Item Name</h3>
			<p>Date</p>
		</section>

	</div>
	<div class="4u">

		<section class="box special">
			<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
			<h3>News Item Name</h3>
			<p>Date</p>
		</section>

	</div>
	<div class="4u">

		<section class="box special">
			<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
			<h3>News Item Name</h3>
			<p>Date</p>
		</section>

	</div>

</div>	 -->

<a name="contact" />


<div class="row">
	<div class="6u"> 

		<section class="box special">
			<h3>Join Us</h3>
			<p>Sign up to our mailing list for updates, info on rescue recitals and more</p>

			{% include mailchimp.html %}

		</section>

	</div>
	<div class="6u">

		<section class="box special">
			<h3>Make a donation</h3>
			<p>Donate to SOS as we build an independent fund at the Pittsburgh Foundation dedicated to supporting the PSO musicians. .</p>
			

			<ul class="actions">
				<li><a href="https://squareup.com/store/save-our-symphony-pittsburgh/item/support-save-our-symphony" target="_blank" class="button">Donate Now</a>
</li>
			</ul>

		</section>   

	</div>
</div>

<section class="box special">
	<header class="major">
		<h2>Questions about SOS Pittsburgh?</h2>
		<p>
			We'd love to hear from you! Use the form below to send us a message and we'll get back to you as soon as we can.
		</p>
	</header>
	{% include contact-form.html %}
</section>
	
	
<a name="upcoming-events" />

<!--		
<div class="row">
	<div class="12u">
		<header class="major">
			<h2>Upcoming Concerts at the PSO 
			</h2>
		</header>
	</div>

	  <div id="rss-feeds"></div>
	  <div id="rss-feeds-test"></div>
		


		<div class="3u">

			<section class="box special">
				<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
				<h3>Concert Name</h3>
				<p>Date</p>
			</section>

		</div>
		<div class="3u">

			<section class="box special">
				<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
				<h3>Concert Name</h3>
				<p>Date</p>
			</section>

		</div>
		<div class="3u">

			<section class="box special">
				<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
				<h3>Concert Name</h3>
				<p>Date</p>
			</section>

		</div>		
		<div class="3u">

			<section class="box special">
				<span class="image featured"><img src="{{ site.baseurl }}/assets/images/pic02.jpg" alt="" /></span>
				<h3>Concert Name</h3>
				<p>Date</p>
			</section>

		</div>
</div>	


-->