<template>
	<Backdrop>
		<div class="ml-navbar py-top-offset">
			<StoriesEditor></StoriesEditor>
		</div>
	</Backdrop>
</template>

<script>
	import { defineComponent } from 'vue';
	import ANTAXAttribution from '@D/components/attributions/ANTAXAttribution.vue';
    import Backdrop from '@D/components/general/modals/Backdrop.vue';
	import StoriesEditor from '@D/components/stories/editor/StoriesEditor.vue';

	export default defineComponent({
		components: {
			StoriesEditor: StoriesEditor,
			ANTAXAttribution: ANTAXAttribution,
			Backdrop: Backdrop
		}
	});
</script>