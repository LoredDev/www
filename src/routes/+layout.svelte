<script lang="ts">
	import '@fontsource-variable/fira-code';
	import '@fontsource-variable/inter';
	import 'cal-sans';
	import 'virtual:uno.css';
	import '../app.scss';
</script>

<main
	un-text="gray12"
	un-font="sans"
	un-p="x-3ch lg:0"
	un-top="0"
	un-left="0"
	un-flex="~ col"
	un-justify="center"
	un-items="center"
>
	<slot />
</main>
<footer
	un-text="gray9 xs center"
	un-font="sans light"
	un-flex="~ col"
	un-justify="center"
	un-bottom="5"
>
	<p>
		<a
			href="https://creativecommons.org/licenses/by-sa/4.0/"
			ref="nofollow noopener noreferrer"
			target="_blank"
			reset-style
			un-transition="all duration-0.5s delay-0"
			un-color="gray9"
			un-decoration="gray2 hover:gray5 offset-3 1"
		>
			CC BY-SA 4.0 2023-PRESENT
		</a>
		&copy Gustavo "Guz" L. de Mello
	</p>
</footer>
