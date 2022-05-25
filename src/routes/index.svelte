<script context="module">
	export const prerender = true;
</script>

<script>
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	<div class="wrapper">
		<div class="collectionsContainerTwo" />
		<div class="collectionsContainer" />
			<p>Collections</p>
			<hr />
			<p>Categories</p>
			<ul>
				<li><a href="/">Sounds</a></li>
				<li><a href="/">Drums</a></li>
				<li><a href="/">Instruments</a></li>
				<li><a href="/">Audio Effects</a></li>
				<li><a href="/">Plug-Ins</a></li>
				<li><a href="/">Clips</a></li>
				<li><a href="/">Samples</a></li>
				<li><a href="/">Grooves</a></li>
				<li><a href="/">Templates</a></li>
			</ul>
			<hr />
		</div>
		<div class="collectionsContainerTwo" />
	</div>
</section>

<style>
	section {
		display: flex;
		justify-content: space-between;
		flex: 1;
	}
	img {
		background-size: 1em 1em;
	}
	.wrapper {
		display: flex;
		justify-content: space-between;
	}
	p {
		font-weight: bold;
		font-size: 14px;
	}
	ul {
		margin: 0;
		padding: 0;
		list-style-type: none;
	}
	a {
		color: black;
		font-size: 14px;
	}
	.collectionsContainer {
		float: left;
		background-color: silver;
		color: black;
		cursor: default;
		width: auto;
		border: 2px double rgba(0, 0, 0, 0.5);
		padding: 0.5em;
	}
	.collectionsContainerTwo {
		float: left;
		background-color: silver;
		color: black;
		cursor: default;
		width: auto;
		border: 4px double rgba(0, 0, 0, 0.5);
		padding: 0.5em;
		background-image: linear-gradient(#444cf7 1px, transparent 1px),
			linear-gradient(to right, #444cf7 1px, #292949 1px);
		background-size: 10px 10px;
	}
</style>
