<script>
	export let style;
	export let text;

	let style_component = {
		primary: 'btn-primary',
		secondary: 'btn-secondary',
		danger: 'btn-danger',
		success: 'btn-success',
		warning: 'btn-warning',
		info: 'btn-info',
		light: 'btn-light',
		dark: 'btn-dark',
		link: 'btn-link'
	};
</script>

<button class="btn {style_component[style]}">{text}</button>
