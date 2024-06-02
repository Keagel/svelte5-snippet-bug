<script lang="ts">
    type Props = {
        helperTextPosition: 'inline-left' | 'inline-right' | 'popup' | 'below';
    };
</script>

{#snippet popupButton(classes: string = '')}
	<button
		type="button"
		class="[&>*]:pointer-events-none {classes}"
	>
        Button
	</button>
{/snippet}
