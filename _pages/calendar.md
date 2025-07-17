---
layout: page
title: "Calendar"
permalink: /calendar/
---

<div id="upcoming"></div>
<div class="span9">
	<h3>West Sound DSA Events</h3>

	<div class="calendar-desktop">
		<iframe
			src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FLos_Angeles&showPrint=0&title=West%20Sound%20DSA&src=d2VzdHNvdW5kZHNhQGdtYWlsLmNvbQ&color=%23d50000"
			style="border:solid 1px #777" width="100%" height="600" frameborder="0" scrolling="no"></iframe>
	</div>
	<div class="calendar-mobile">
		<iframe
			src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FLos_Angeles&showPrint=0&title=West%20Sound%20DSA&mode=AGENDA&src=d2VzdHNvdW5kZHNhQGdtYWlsLmNvbQ&color=%23d50000"
			style="border:solid 1px #777" width="100%" height="600" frameborder="0" scrolling="no"></iframe>
	</div>

</div>

<style>
	.calendar-desktop {
		display: block;
	}

	.calendar-mobile {
		display: none;
	}

	@media (max-width: 992px) {
		.calendar-desktop {
			display: none;
		}

		.calendar-mobile {
			display: block;
		}
	}
</style>