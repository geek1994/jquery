# jquery
// on scroll add and remove class//

<script>
	$(window).scroll(function() {
		if ($(this).scrollTop() > 1) {
			$('.animenu').addClass("sticky");
		} else {
			$('.animenu').removeClass("sticky");
		}
	});
</script>
