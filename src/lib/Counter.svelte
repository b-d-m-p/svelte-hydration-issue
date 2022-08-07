<script>
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>

<div class="ml-24 mt-24">

	<button class="bg-green-100 p-4" on:click={handleClick}>
		Clicked {count} {count === 1 ? 'time' : 'times'}
	</button>
	

</div>

<style>
	
</style>
