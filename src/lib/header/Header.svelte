<script>
	import { page } from '$app/stores';
</script>

<header>
	<div class="corner">
		<a sveltekit:prefetch href="/">patchwerk.io</a>
		<!-- <a href="/">Sign Up</a>
		<a href="/">Discord</a> -->
	</div>

	<!-- <nav> -->
	<!-- <ul>
		<li class:active={$page.url.pathname === '/'}><a sveltekit:prefetch href="/">Home</a></li>
		<li class:active={$page.url.pathname === '/about'}>
			<a sveltekit:prefetch href="/about">About</a>
		</li>
		<li class:active={$page.url.pathname === '/todos'}>
			<a sveltekit:prefetch href="/todos">Todos</a>
		</li>
	</ul> -->
	<!-- </nav> -->
</header>

<style>
	header {
		/* border: 4px double rgba(0, 0, 0, 0.5); */
		display: block;
		top: 0;
		left: 0;
		right: 0;
		z-index: 10;
		background: silver;
		padding: 0.5em;
		border: 4px double rgba(0, 0, 0, 0.5);
		box-shadow: 0 0 0 3px #373742, 1em 1em 3px 0 rgb(0 0 0 / 50%);
	}

	a {
		color: black;
		font-size: 18px;
	}
</style>
