<script>
	import Button from '../components/Button.svelte';
</script>

<svelte:head>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css"
	/>
</svelte:head>

<main>
	<Button style="primary" text="Primary" />
	<Button style="secondary" text="Secondary" />
	<Button style="danger" text="Danger" />
	<Button style="success" text="Success" />
	<Button style="warning" text="Warning" />
	<Button style="info" text="Info" />
	<Button style="light" text="Light" />
	<Button style="dark" text="Dark" />
	<Button style="link" text="Link" />
	<button class="btn btn-outline-primary">outline-primary</button>
	<button class="btn btn-outline-secondary">outline-secondary</button>
	<button class="btn btn-outline-danger">outline-danger</button>
	<button class="btn btn-outline-success">outline-success</button>
	<button class="btn btn-outline-warning">outline-warning</button>
	<button class="btn btn-outline-info">outline-info</button>
	<button class="btn btn-outline-light">outline-light</button>
	<button class="btn btn-outline-dark">outline-dark</button>

	<button class="btn btn-sm btn-primary">primary</button>
	<button class="btn btn-sm btn-secondary">secondary</button>
	<button class="btn btn-sm btn-danger">danger</button>
	<button class="btn btn-sm btn-success">success</button>
	<button class="btn btn-sm btn-warning">warning</button>
	<button class="btn btn-sm btn-info">info</button>
	<button class="btn btn-sm btn-light">light</button>
	<button class="btn btn-sm btn-dark">dark</button>
	<button class="btn btn-sm btn-link">link</button>
	<button class="btn btn-sm btn-outline-primary">outline-primary</button>
	<button class="btn btn-sm btn-outline-secondary">outline-secondary</button>
	<button class="btn btn-sm btn-outline-danger">outline-danger</button>
	<button class="btn btn-sm btn-outline-success">outline-success</button>
	<button class="btn btn-sm btn-outline-warning">outline-warning</button>
	<button class="btn btn-sm btn-outline-info">outline-info</button>
	<button class="btn btn-sm btn-outline-light">outline-light</button>
	<button class="btn btn-sm btn-outline-dark">outline-dark</button>

	<button class="btn btn-primary"><em class=" bi-alarm" /> primary icon</button>
	<button class="btn btn-sm btn-primary"><em class=" bi-alarm" /> primary icon</button>

	<div class="btn-group">
		<button class="btn btn-light"><em class="bi-text-left" /></button>
		<button class="btn btn-light"><em class="bi-text-center" /></button>
		<button class="btn btn-light"><em class="bi-text-right" /></button>
	</div>
</main>
