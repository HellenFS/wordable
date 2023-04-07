<script>
	import '../app.postcss';
</script>

<div class="flex flex-col h-screen">
	<div class="flex-none h-16 bg-orange-500">
		<!-- <span>Header</span> -->
	</div>
	<div class="grow h-14 bg-gray-100 px-4 py-4">
		<slot />
	</div>
	<div class="flex-none h-16 bg-orange-600">
		<!-- <span>NavBar</span> -->
	</div>
</div>
