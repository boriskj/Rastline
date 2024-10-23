<script lang="ts">
	import type { Opis } from './types';

	//export let name: string;
	//export let image: string;
	//export let description: string;
	export let opis: Opis;

	const { name, image, description } = opis;
</script>

<div class="bg-cyan-100 border-cyan-950 border-4 rounded-2xl">
	<h1 class="font-bold">{name.toUpperCase()}</h1>
	<img class="rounded-lg" src={image} />
	<p>
		{description}
	</p>
	<button class="py-2 px-5 bg-cyan-950 text-white font-semibold rounded-full shadow-md"
		>PREBERI VEČ</button
	>
</div>
