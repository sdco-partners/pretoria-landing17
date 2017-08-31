---
title: Home
process: 
  markdown: true
  twig: true
metadata:
  refresh: 30
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
					{{ file_get_contents('assets/svg/svg-brewers.svg') }}
				</div>
				<div class="farmers">
					{{ file_get_contents('assets/svg/svg-farmers.svg') }}
				</div>		
			</div>
			<div class="this-right">
				<h3>to produce slow beer with ingredients sewn in the Georgia soil</h3>
				<div class="imprint-logo">
					{{ file_get_contents('assets/svg/svg-pretoria.svg') }}
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
	<form>
		<input type="email" name="email" placeholder="type in your email address" class="f-email">
		<input type="submit"class="f-submit">
	</form>
</section>