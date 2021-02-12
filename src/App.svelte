<script>
	import Carousel from './Carousel.svelte';
	const images = [
		{
			path: 'https://picsum.photos/id/1012/3973/2639',
			id: 'imagen-ejemplo-1',
			alt: 'Atributo ALT de ejemplo para la imagen #1',
		},
		{
			path: 'https://picsum.photos/id/1005/5760/3840',
			id: 'imagen-ejemplo-2',
			alt: 'Atributo ALT de ejemplo para la imagen #2',
		},
		{
			path: 'https://picsum.photos/id/1020/4288/2848',
			id: 'imagen-ejemplo-3',
			alt: 'Atributo ALT de ejemplo para la imagen #3',
		},
		{
			path: 'https://picsum.photos/id/1025/4951/3301',
			id: 'imagen-ejemplo-4',
			alt: 'Atributo ALT de ejemplo para la imagen #4',
		},
		{
			path: 'https://picsum.photos/id/103/2592/1936',
			id: 'imagen-ejemplo-5',
			alt: 'Atributo ALT de ejemplo para la imagen #5',
		},
		{
			path: 'https://picsum.photos/id/104/3840/2160',
			id: 'imagen-ejemplo-6',
			alt: 'Atributo ALT de ejemplo para la imagen #6',
		},
	];
</script>

<main>
	<h2 class="item__title">Mi galería de ejemplo</h2>
	<div class="item__gallery">
		<Carousel {images} imageHeight={140} imageSpacing={3} />
	</div>
	<p class="item__description">
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae ipsum
		possimus accusamus aut, assumenda fuga labore provident, non molestiae
		recusandae harum, fugit neque nisi quos qui nulla. Non, quaerat officia.
	</p>
</main>

<style>
	main {
		padding: 1em;
		max-width: 800px;
		margin: 0 auto;
	}
</style>
