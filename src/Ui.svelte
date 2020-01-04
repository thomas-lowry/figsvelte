<script>

	//CSS
	import { GlobalCSS } from 'figma-plugin-ds-svelte';

	//import some components
	import { Button } from 'figma-plugin-ds-svelte';
	import { Input } from 'figma-plugin-ds-svelte';
	import { Icon } from 'figma-plugin-ds-svelte';
	import { IconVisible } from 'figma-plugin-ds-svelte';
	import { IconWarning } from 'figma-plugin-ds-svelte';

	function createShapes() {



	}

</script>

<Button primary>Click me</Button>
<Input iconName={IconVisible} />
<Icon iconName={IconVisible} />
<Icon iconName={IconWarning} />

<style>

</style>