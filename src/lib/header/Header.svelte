<script>
	import { page } from '$app/stores';
</script>

<header>
	<div class="corner"><a sveltekit:prefetch href="/">patchwerk.io</a></div>

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
		display: block;
		top: 0;
		left: 0;
		right: 0;
		z-index: 10;
		background: silver;
		border: 2px double rgba(0, 0, 0, 0.5);
	}

	a {
		color: black;
		font-size: 12px;
	}

	.corner {
		width: 3em;
		height: 1.5em;
	}
</style>
