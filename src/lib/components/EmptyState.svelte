<script>
	export let emptyTitle = 'Tidak ada transaksi';
	import illustration from '$lib/assets/images/empty-illustration.png';
</script>

<div class="empty-state-container">
	<img src={illustration} alt="empty illustration" loading="lazy" />
	<p>{emptyTitle}</p>
</div>

<style>
	.empty-state-container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		row-gap: 1rem;
	}

	.empty-state-container > img {
		height: 120px;
	}

	.empty-state-container > p {
		color: var(--darkBlue);
		text-align: center;
		font-size: 0.875rem;
	}
</style>
