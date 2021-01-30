<script>
	import SelectablePlan from "./components/selectablePlan.svelte";
</script>

<div id="app" class="min-h-screen bg-gray-200 font-sans">
	<div class="md:w-3/5 mx-auto pt-8 pb-6 md:flex md:justify-between items-end border-b-2 border-grey">
		<div class="text-2xl text-blue-darker mb-4 md:mb-0">Change Plan</div>
		<div>
			<a href="/#" class="no-underline text-blue-darker hover:underline">Cancel your plan</a>
		  </div>
	</div>

	<SelectablePlan>

	</SelectablePlan>
</div>