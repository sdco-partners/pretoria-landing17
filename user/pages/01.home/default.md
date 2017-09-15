---
title: Home
process: 
  markdown: true
  twig: true
metadata:
  authors: 'SDCO Partners'
  keywords: 'Beer, Brewers, Georgia, Farmers'
  description: 'Farmers and Brewers working together to brew beer from Georgia soil'
---



{# ==== SECTION: FLOATING-ELEMENTS ==== #}
<section class="floating-elements">
	<div class="about">
		<div class="about-wrapper">
			<div class="this-left">
				<h2>We’re a collective of brewers and farmers working together</h2>
			</div>
			<div class="this-middle">
				<div class="brewers">
					{{ file_get_contents('user/themes/blastoid/assets/svg/svg-brewers.svg') }}
				</div>
				<div class="farmers">
					{{ file_get_contents('user/themes/blastoid/assets/svg/svg-farmers.svg') }}
				</div>		
			</div>
			<div class="this-right">
				<h3>to produce slow beer with ingredients sewn in the Georgia soil</h3>
				<div class="imprint-logo">
					{{ file_get_contents('user/themes/blastoid/assets/svg/svg-pretoria.svg') }}
				</div>
			</div>
		</div>
	</div>

	<div class="seals">
		<div class="seal-wrapper">
			<div class="left-seal"></div>
			<div class="middle-seal"></div>
			<div class="right-seal"></div>
	  </div>
	</div>
</section>


{# ==== SECTION: NEWSLETTER ==== #}
<section class="newsletter">
	<h3 class="tagline">Want to know more? Sign up for our newsletter.</h3>
	<form action="//pretoriafields.us14.list-manage.com/subscribe/post-json?u=897debc7b273cedcf6b179d76&amp;id=a7e47986e6&amp;c=?" 
	  method="get" id="mc-embedded-subscribe-form" 
	  name="mc-embedded-subscribe-form" class="validate" 
	  target="_blank" novalidate>
		<input type="email" name="EMAIL" placeholder="type in your email address" class="f-email email" id="mce-EMAIL" required>
		<div id="mce-responses" class="clear">
	    <div class="response" id="mce-error-response" style="display:none"></div>
	    <div class="response" id="mce-success-response" style="display:none"></div>
	  </div>
	  <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
		<div style="position: absolute; left: -5000px;" aria-hidden="true">
			<input type="text" name="b_897debc7b273cedcf6b179d76_a7e47986e6" tabindex="-1" value="">
		</div>
		<input type="submit" class="f-submit button" id="mc-embedded-subscribe" value="Subscribe">
	</form>
</section>