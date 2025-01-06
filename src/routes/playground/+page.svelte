<script>
	let sample = `
f x = x^2

graph(f)`;

	async function runCode() {
		const WORKERS_URL = 'https://worker-rust.megatank.workers.dev';
		const result = await (
			await fetch(
				new Request(WORKERS_URL, {
					method: 'POST',
					body: JSON.stringify({
						code: document.getElementById('code').value.split('# OUTPUT:')[0].trim(),
						debug: false
					})
				})
			)
		).text();

		document.getElementById('code').value =
			`${document.getElementById('code').value.split('# OUTPUT:')[0].trim()}

# OUTPUT:
# ANYTHING BELOW THIS LINE IS ALWAYS IGNORED, YOU DO NOT NEED TO REMOVE ANYTHING
${result}`;
	}
</script>

<div class="my-2 mx-20 p-4 text-center">
	<div class="mockup-browser shadow-2xl">
		<div class="mockup-browser-toolbar">
			<div class="input border border-base-300">Calcagebra</div>
			<h1 class="flex">
				<button class="btn btn-primary rounded-2xl ml-auto" on:click={runCode}>EXEC</button>
			</h1>
		</div>
		<div class="flex border-t border-base-300 min-h-screen">
			<textarea id="code" class="textarea textarea-lg text-sm text-light bg-base-100 min-h-screen w-full"
				>{sample}</textarea
			>
		</div>
	</div>
</div>
