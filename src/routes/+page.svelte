<script lang="ts">
	$: currentYear = new Date().getFullYear();
</script>

<div class="hero min-h-screen" style="background-image: url(/image/fries.jpg);">
	<div class="hero-overlay bg-opacity-60" />
	<div class="hero-content text-center text-white">
		<div class="max-w-md">
			<p class="text-xl">Welcome to</p>
			<h1 class="mb-5 text-5xl font-bold">OnlyFries</h1>
			<p class="mb-5">The place to be for everything fries related.</p>
		</div>
	</div>
</div>

<section class="text-center my-5">
	<h2 class="text-2xl">Construction</h2>
	<p>This website is currently under construction. Please come back later.</p>
</section>

<footer class="footer footer-center p-10 bg-primary text-primary-content">
	<aside>
		<svg
			width="50"
			height="50"
			viewBox="0 0 24 24"
			xmlns="http://www.w3.org/2000/svg"
			fill-rule="evenodd"
			clip-rule="evenodd"
			class="inline-block fill-current"
			><path
				d="M22.672 15.226l-2.432.811.841 2.515c.33 1.019-.209 2.127-1.23 2.456-1.15.325-2.148-.321-2.463-1.226l-.84-2.518-5.013 1.677.84 2.517c.391 1.203-.434 2.542-1.831 2.542-.88 0-1.601-.564-1.86-1.314l-.842-2.516-2.431.809c-1.135.328-2.145-.317-2.463-1.229-.329-1.018.211-2.127 1.231-2.456l2.432-.809-1.621-4.823-2.432.808c-1.355.384-2.558-.59-2.558-1.839 0-.817.509-1.582 1.327-1.846l2.433-.809-.842-2.515c-.33-1.02.211-2.129 1.232-2.458 1.02-.329 2.13.209 2.461 1.229l.842 2.515 5.011-1.677-.839-2.517c-.403-1.238.484-2.553 1.843-2.553.819 0 1.585.509 1.85 1.326l.841 2.517 2.431-.81c1.02-.33 2.131.211 2.461 1.229.332 1.018-.21 2.126-1.23 2.456l-2.433.809 1.622 4.823 2.433-.809c1.242-.401 2.557.484 2.557 1.838 0 .819-.51 1.583-1.328 1.847m-8.992-6.428l-5.01 1.675 1.619 4.828 5.011-1.674-1.62-4.829z"
			/></svg
		>
		<p class="font-bold">
			OnlyFries<br />Providing quality metrics on fries since 2001.
		</p>
		<p>
			Made possible by <a
				href="https://jonasclaes.be?ref=onlyfri.es"
				class="link"
				target="_blank"
				rel="noopener noreferrer">jonasclaes.be</a
			>.
		</p>
		<p>Copyright © {currentYear} - All rights reserved</p>
	</aside>
	<nav>
		<div class="grid grid-flow-col gap-4">
			<p>
				Want to become our brand ambassador?<br />
				Send an email to
				<a href="mailto:jonas@jonasclaes.be" class="link">jonas@jonasclaes.be</a>.
			</p>
		</div>
	</nav>
</footer>
