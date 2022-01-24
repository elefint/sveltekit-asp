<script>
	import { onMount } from 'svelte';
	import { themeChange } from 'theme-change';
	onMount(async () => {
		themeChange(false);
	});
	// must use onMount because we don't want it on SSR.
</script>

<!-- <button data-toggle-theme="dracula,cupcakeß" data-act-class="ACTIVECLASS">toggle theme</button> -->
<select data-choose-theme class="select select-bordered w-full max-w-xs">
	<option value="light">Light</option>
	<option value="dark">Dark</option>
	<option value="cupcake">Cupcake</option>
	<option value="Emerald">Emerald</option>
	<option value="Corporate">Corporate</option>
	<option value="synthwave">Snythwave</option>
	<option value="retro">Retro</option>
	<option value="cyberpunk">Cyberpunk</option>
	<option value="valentine">Valentine</option>
	<option value="halloween">Halloween</option>
	<option value="garden">Garden</option>
	<option value="forest">Forest</option>

</select>

<style>
</style>
