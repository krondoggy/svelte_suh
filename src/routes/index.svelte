<script context="module">
	export const prerender = true;
	import folderClosed from '$lib/assets/folder_closed.png';
	import folderOpened from '$lib/assets/folder_opened.png';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<div>
	<div class="searchContainer">
		<input type="search" placeholder="Search..." />
		<button>Search</button>
	</div>

	<section>
		<div class="wrapper">
			<div class="collectionsContainer">
				<p>Collections</p>
				<hr />
				<p>Categories</p>
				<ul>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Sounds</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Drums</a>
					</li>
					<li>
						<img class="folderIcon" src={folderOpened} alt="closed folder" />
						<a href="/">Instruments</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Audio Effects</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Plug-Ins</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Clips</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Samples</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Grooves</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Templates</a>
					</li>
				</ul>
				<hr />
			</div>
			<div class="collectionsContainer">
				<ul>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-1</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-2</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-3</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-4</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-5</a>
					</li>
					<li>
						<img class="folderIcon" src={folderOpened} alt="closed folder" />
						<a href="/">Item-6</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-7</a>
					</li>
					<li>
						<img class="folderIcon" src={folderClosed} alt="closed folder" />
						<a href="/">Item-8</a>
					</li>
				</ul>
			</div>
			<div class="collectionsContainerTwo" />
			<div class="containerMain">
				<fieldset>
					<legend>Instruments &#8594; Sub Item &#8594; List View</legend>
					<hr />
					<table>
						<tr>
							<th>Title</th>
							<th>Author</th>
							<th>Date</th>
						</tr>
						<tr>
							<td>First</td>
							<td>Second</td>
							<td>Third</td>
						</tr>
						<tr>
							<td>1</td>
							<td>2</td>
							<td>3</td>
						</tr>
						<tr>
							<td>1</td>
							<td>2</td>
							<td>3</td>
						</tr>
					</table>
				</fieldset>
			</div>
		</div>
	</section>
</div>

<style>
	section {
		display: flex;
		justify-content: space-between;
		flex: 1;
	}
	.wrapper {
		display: flex;
		justify-content: space-between;
		width: 100%;
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
	li {
		align-items: center;
		justify-content: center;
	}
	a {
		color: black;
		font-size: 14px;
	}
	.folderIcon {
		height: 10px;
		width: 10px;
	}
	.searchContainer {
		/* background-color: silver; */
		color: black;
		cursor: default;
		font-size: 12px;
		width: 30%;
		/* border: 4px double rgba(0, 0, 0, 0.5); */
		padding: 0.5em;
	}
	.collectionsContainer {
		float: left;
		background-color: silver;
		color: black;
		cursor: default;
		width: 15%;
		border: 4px double rgba(0, 0, 0, 0.5);
		padding: 0.5em;
		box-shadow: 0 0 0 3px #373742, 1em 1em 3px 0 rgb(0 0 0 / 50%);
	}
	.collectionsContainerTwo {
		float: left;
		/* background-color: silver; */
		color: black;
		cursor: default;
		/* width: 0.01em; */
		width: auto;
		/* border: 4px double rgba(0, 0, 0, 0.5); */
		padding: 0.5em;
		/* background-image: linear-gradient(#444cf7 1px, transparent 1px),
			linear-gradient(to right, #444cf7 1px, #292949 1px);
		background-size: 10px 10px; */
	}
	.containerMain {
		float: left;
		background-color: silver;
		color: black;
		cursor: default;
		/* width: 63em; */
		width: 70%;
		border: 4px double rgba(0, 0, 0, 0.5);
		padding: 0.5em;
		box-shadow: 0 0 0 3px #373742, 1em 1em 3px 0 rgb(0 0 0 / 50%);
	}
</style>
