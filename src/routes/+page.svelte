<script lang="ts">
	import Input from '$lib/Input.svelte';

	let valueInputSearch = '';

	async function getWordMeaning() {
		alert(`Pesquisar por: ${valueInputSearch}`);
	}
</script>

<Input
	id="search-word"
	placeholder={'Search by...'}
	onSubmit={() => getWordMeaning()}
	bind:value={valueInputSearch}
/>
