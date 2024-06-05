<script>
	let output = `
⣣⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⡇⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⡁
⡁⠑⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠔⠁⡁ 25.0
⠄⠀⠈⠢⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⠊⠀⠀⠄
⠂⠀⠀⠀⠑⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠜⠀⠀⠀⠀⠂
⡁⠀⠀⠀⠀⠀⠑⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠔⠁⠀⠀⠀⠀⠀⡁
⠄⠀⠀⠀⠀⠀⠀⠀⠑⢄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠔⠁⠀⠀⠀⠀⠀⠀⠀⠄
⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠢⢄⡀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⣀⠤⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂
⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠒⠢⢄⣀⡀⠀⠀⡇⠀⠀⣀⣀⠤⠒⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡁
⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠉⠉⠉⠉⠉⠉⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁
-5.0                  0.0                    5.0
`;
</script>

<div class="hero min-h-screen bg-base-200">
	<div class="hero-content flex-col lg:flex-row-reverse gap-24">
		<div class="grid grid-cols-3 grid-rows-2 gap-1 place-items-end">
			<div
				class="mockup-code rounded-lg shadow-2xl bg-base-100 text-base-content h-32 animate-slidein [--slidein-delay:500ms] opacity-0"
			>
				<pre data-prefix="%"><code>{'f x = x^2\n\t graph(f)'}</code></pre>
			</div>
			<div></div>
			<div></div>
			<div></div>
			<div
				class="mockup-code rounded-lg shadow-2xl bg-base-100 text-base-content text-xs col-span-2 animate-slidein [--slidein-delay:700ms] opacity-0"
			>
				<pre data-prefix="$ calcagebra run example.cal" class="px-8"><code
						>{output}
					</code></pre>
			</div>
		</div>
		<div>
			<h1 class="text-5xl font-bold animate-slidein [--slidein-delay:300ms] opacity-0">
				Calcagebra
			</h1>
			<p class="py-6 animate-slidein [--slidein-delay:500ms] opacity-0">
				Programming language for evaluating mathematical expressions.
			</p>
			<button class="btn btn-primary animate-slidein [--slidein-delay:700ms] opacity-0"
				>Get Started</button
			>
		</div>
	</div>
</div>
