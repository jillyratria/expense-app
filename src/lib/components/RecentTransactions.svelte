<script>
	import EmptyState from './EmptyState.svelte';
</script>

<div class="recent-container">
	<h2>Recent Transactions</h2>
	<EmptyState />
</div>

<style>
	.recent-container {
		padding: 1rem;
		padding-top: 1.5rem;
		margin-top: -1.5rem;
		background-color: #ffffff;
		border-radius: 1.5rem 1.5rem 0 0;
		min-height: 50vh;
	}
	h2 {
		font-size: 1rem;
		margin: 0;
		margin-bottom: 1rem;
	}
</style>
