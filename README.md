# Responsive Google or Bing maps
If you are looking for an easy and fully responsive solution to embed Google or Bing maps on your website, you might want to try this CSS technique.

Apparently a lot of developers struggle to embed Google or Bing maps in responsive designs. As far I am concerned you can solve this with a very easy CSS technique.

You can see a live preview here: <a href='https://codepen.io/niklausgerber/pen/KazyGX' title='Responsive Google or Bing maps Live Preview' target='_blank'>Responsive Google or Bing maps Live Preview</a>

## CSS
Make sure you include the following CSS code on your website.

	/* Flexible iFrame */
	
	.Flexible-container {
	    position: relative;
	    padding-bottom: 56.25%;
	    padding-top: 30px;
	    height: 0;
	    overflow: hidden;
	}
	
	.Flexible-container iframe,   
	.Flexible-container object,  
	.Flexible-container embed {
	    position: absolute;
	    top: 0;
	    left: 0;
	    width: 100%;
	    height: 100%;
	}
	

## HTML
Place following HTML Code directly in your HTML.	

	<!-- Responsive iFrame -->
	<div class="Flexible-container">
	    <iframe width="425" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.ch/maps?f=q&amp;source=s_q&amp;hl=de&amp;geocode=&amp;q=Bern&amp;aq=&amp;sll=46.813187,8.22421&amp;sspn=3.379772,8.453979&amp;ie=UTF8&amp;hq=&amp;hnear=Bern&amp;t=m&amp;z=12&amp;ll=46.947922,7.444608&amp;output=embed&amp;iwloc=near"></iframe>
	</div>

The DIV Flexible-container is the responsive container for the map. You can also place it inside another DIV if you like. The map embed code will then be placed inside the Flexible-container DIV. That is all. It will also work with any other iFrame embed.

## Credits
Please support humans.txt (http://humanstxt.org/). It's an initiative for knowing the people behind a website. It's a TXT file that contains information about the different people who have contributed to building the website.

	Responsive Google or Bing maps: https://github.com/niklausgerber/responsive-google-or-bing-maps
	Niklaus Gerber
	Twitter: @niklausgerber
	URL: https://www.niklausgerber.com
	Location: Zürich, Switzerland

## Download, Fork, Commit.
If you think you can make this better, please Download, Fork, & Commit. I'd love to see your ideas.

## Donation
I love to create and I won't ask for repayment. If you appreciate my work and would like to support me I am sure you will earn some extra Karma points. <a href="https://www.paypal.me/NiklausGerber" target="_blank" title="Please donate">Please donate</a>.