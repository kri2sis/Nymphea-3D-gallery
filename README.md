Nymphea-3D-gallery
==================

3D images gallery for web site made only with CSS and HTML

Based on css transform properties, i'd like to make my first CSS slider animated.
Hope you could enjoy.

For SEO, images are include in html
and for the Javascript ennemies, css will be seen by all (even the partially-sighted persons and the visually handicapped people)



just add that if you want to stop animation by hover on image you hover
<script>
$(document).ready(function(){
		$('.image').hover(function(){
			$(this).parent().css('-webkit-animation-play-state', 'paused');}, function(){
				$(this).parent().css('-webkit-animation-play-state', 'running');
			})
	
	})
	</script>
