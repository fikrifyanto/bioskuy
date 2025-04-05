<script lang="ts">
	import '../app.css';
	import '@fontsource/poppins';
	
	let { children } = $props();
</script>

<div class="font-poppins bg-slate-200">
	{@render children()}
</div>
