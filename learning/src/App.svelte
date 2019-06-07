<script>
	import Nested from './Nested.svelte';
	let name = 'world';
	let who = 'A man';
	let src = 'https://svelte.dev/tutorial/image.gif';
</script>

<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS';
		font-size: 2em;
	}
</style>

<h1>Hello {name}!</h1>
<img {src} alt="{who} dancing" />
<p>This is a paragraph with component scoped styles</p>
<Nested />
