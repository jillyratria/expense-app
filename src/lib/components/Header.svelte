<script>
	/**
	 * @type {string}
	 */
	export let title;
</script>

<header>
	<h1 class="page-title">{title}</h1>
</header>

<style>
	header {
		background-color: var(--paleCyan);
		min-height: 60px;
		padding: 0 16px;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.page-title {
		font-size: 16px;
		margin: 0;
		color: var(--darkBlue);
		letter-spacing: 1px;
		text-transform: uppercase;
		font-weight: 600;
	}
</style>
