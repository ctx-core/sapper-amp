<svelte:head>
	<script async src="https://cdn.ampproject.org/v0.js"></script>
	<script
		async
		custom-element="amp-form"
		src="https://cdn.ampproject.org/v0/amp-form-0.1.js"
	></script>
	<noscript>
		<style amp-boilerplate>
			body {
				-webkit-animation: none;
				-moz-animation: none;
				-ms-animation: none;
				animation: none;
			}
		</style>
	</noscript>
</svelte:head>

<slot></slot>

<style amp-boilerplate>
	:global(body) {
		-webkit-animation: -amp-start 8s steps(1, end) 0s 1 normal both;
		-moz-animation: -amp-start 8s steps(1, end) 0s 1 normal both;
		-ms-animation: -amp-start 8s steps(1, end) 0s 1 normal both;
		animation: -amp-start 8s steps(1, end) 0s 1 normal both;
	}
	@-webkit-keyframes -amp-start {
		from {
			visibility: hidden;
		}
		to {
			visibility: visible;
		}
	}
	@-moz-keyframes -amp-start {
		from {
			visibility: hidden;
		}
		to {
			visibility: visible;
		}
	}
	@-ms-keyframes -amp-start {
		from {
			visibility: hidden;
		}
		to {
			visibility: visible;
		}
	}
	@-o-keyframes -amp-start {
		from {
			visibility: hidden;
		}
		to {
			visibility: visible;
		}
	}
	@keyframes -amp-start {
		from {
			visibility: hidden;
		}
		to {
			visibility: visible;
		}
	}
</style>
