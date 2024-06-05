<script>
	let g1 = `
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

	let g2 = `
⡁⠈⠀⡇⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⣁⡨⠤⠓⠚⠉⡁ 2.3
⠄⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡠⠤⠒⠊⠉⠀⠀⠀⠀⠀⠀⠄
⠂⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡠⠔⠊⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂
⡁⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠔⠊⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡁
⠄⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⡠⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄ 1.3
⠂⠀⠀⡇⠀⠀⠀⠀⠀⠀⡔⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂
⡁⠀⠀⡇⠀⠀⠀⠀⡠⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡁
⠄⠀⠀⡇⠀⠀⠀⡰⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄
⠂⠀⠀⡇⠀⠀⡜⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂ 0.2
⡉⠉⠉⡏⠉⢹⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⡁
⠄⠀⠀⡇⢀⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄
⠂⠀⠀⡇⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂
⡁⠀⠀⡇⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡁ -0.8
⠄⠀⠀⣧⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄
⠂⠀⠀⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂
⡁⠀⠀⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡁
⠁⠈⠀⠉⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁⠈⠀⠁ -1.8
    								10.0
`;

	let c1 = `
F m1 m2 r = G*m1*m2/r^2

print(F(10,5,1))
# 10
`;

	let c2 = `
f x = 4x^3 + 3x^2 - 4x + 5

print(f\`)
# 12x^2 + 6x - 4
`;

	let c3 = `
f x = x

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
${result}`;
	}
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
						>{g1}
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
			<button
				class="btn btn-secondary animate-slidein [--slidein-delay:700ms] opacity-0"
				on:click={() => {
					document.getElementById('timeline').scrollIntoView({
						behavior: 'smooth',
						block: 'start'
					});
				}}>Learn more</button
			>
		</div>
	</div>
</div>
<ul id="timeline" class="timeline timeline-vertical m-4 p-8">
	<li>
		<div class="timeline-start timeline-box py-4 text-center text-4xl font-light">
			Generate graphs of any function on the fly!
		</div>
		<hr />
	</li>
	<li>
		<hr />
		<div class="timeline-end timeline-box">
			<div
				class="mockup-code rounded-lg shadow-2xl bg-base-100 text-base-content text-xs col-span-2 animate-slidein [--slidein-delay:700ms] opacity-0"
			>
				<pre data-prefix="% f x = log(x)" class="px-8"><code
						>{g2}
				</code></pre>
			</div>
		</div>
		<hr />
	</li>
	<li>
		<hr />
		<div class="timeline-start timeline-box py-4 text-center text-4xl font-light">
			Create functions and generate values for different arguments
		</div>
		<hr />
	</li>
	<li>
		<hr />
		<div class="timeline-end timeline-box">
			<div
				class="mockup-code rounded-lg shadow-2xl bg-base-100 text-base-content text-xs col-span-2 animate-slidein [--slidein-delay:700ms] opacity-0"
			>
				<pre class="px-8"><code
						>{c1}
				</code></pre>
			</div>
		</div>
		<hr />
	</li>
	<li>
		<hr />
		<div class="timeline-start timeline-box py-4 text-center text-4xl font-light">
			Differentiate functions and more with in-built calculus methods!
		</div>
		<hr />
	</li>
	<li>
		<hr />
		<div class="timeline-end timeline-box">
			<div
				class="mockup-code rounded-lg shadow-2xl bg-base-100 text-base-content text-xs col-span-2 animate-slidein [--slidein-delay:700ms] opacity-0"
			>
				<pre class="px-8"><code
						>{c2}
				</code></pre>
			</div>
		</div>
		<hr />
	</li>
</ul>

<div class="my-2 mx-20 p-4 text-center">
	<h1 class="text-3xl font-bold m-2 p-4">
		<button class="btn btn-neutral rounded-2xl text-3xl" on:click={runCode}>Try out</button> calcagebra
		with the playground or api!
	</h1>
	<div class="mockup-browser shadow-2xl">
		<div class="mockup-browser-toolbar">
			<div class="input border border-base-300">https://playground.megatank58.xyz</div>
		</div>
		<div class="flex border-t border-base-300 h-60">
			<textarea id="code" class="textarea textarea-lg text-sm text-light bg-base-100 h-full w-full"
				>{c3}</textarea
			>
		</div>
	</div>
</div>
<footer class="footer p-10 bg-neutral text-neutral-content gap-1">
	<aside>
		<p class="text-lg">
			megatank58<br />Copyright © 2024 - All right reserved
		</p>
	</aside>
	<nav>
		<h6 class="footer-title">GitHub</h6>
		<div class="grid grid-flow-col gap-4">
			<a href="https://github.com/megatank58"
				><svg xmlns="http://www.w3.org/2000/svg" width="32.77" height="32" viewBox="0 0 256 250"
					><path
						fill="#161614"
						d="M128.001 0C57.317 0 0 57.307 0 128.001c0 56.554 36.676 104.535 87.535 121.46c6.397 1.185 8.746-2.777 8.746-6.158c0-3.052-.12-13.135-.174-23.83c-35.61 7.742-43.124-15.103-43.124-15.103c-5.823-14.795-14.213-18.73-14.213-18.73c-11.613-7.944.876-7.78.876-7.78c12.853.902 19.621 13.19 19.621 13.19c11.417 19.568 29.945 13.911 37.249 10.64c1.149-8.272 4.466-13.92 8.127-17.116c-28.431-3.236-58.318-14.212-58.318-63.258c0-13.975 5-25.394 13.188-34.358c-1.329-3.224-5.71-16.242 1.24-33.874c0 0 10.749-3.44 35.21 13.121c10.21-2.836 21.16-4.258 32.038-4.307c10.878.049 21.837 1.47 32.066 4.307c24.431-16.56 35.165-13.12 35.165-13.12c6.967 17.63 2.584 30.65 1.255 33.873c8.207 8.964 13.173 20.383 13.173 34.358c0 49.163-29.944 59.988-58.447 63.157c4.591 3.972 8.682 11.762 8.682 23.704c0 17.126-.148 30.91-.148 35.126c0 3.407 2.304 7.398 8.792 6.14C219.37 232.5 256 184.537 256 128.002C256 57.307 198.691 0 128.001 0m-80.06 182.34c-.282.636-1.283.827-2.194.39c-.929-.417-1.45-1.284-1.15-1.922c.276-.655 1.279-.838 2.205-.399c.93.418 1.46 1.293 1.139 1.931m6.296 5.618c-.61.566-1.804.303-2.614-.591c-.837-.892-.994-2.086-.375-2.66c.63-.566 1.787-.301 2.626.591c.838.903 1 2.088.363 2.66m4.32 7.188c-.785.545-2.067.034-2.86-1.104c-.784-1.138-.784-2.503.017-3.05c.795-.547 2.058-.055 2.861 1.075c.782 1.157.782 2.522-.019 3.08m7.304 8.325c-.701.774-2.196.566-3.29-.49c-1.119-1.032-1.43-2.496-.726-3.27c.71-.776 2.213-.558 3.315.49c1.11 1.03 1.45 2.505.701 3.27m9.442 2.81c-.31 1.003-1.75 1.459-3.199 1.033c-1.448-.439-2.395-1.613-2.103-2.626c.301-1.01 1.747-1.484 3.207-1.028c1.446.436 2.396 1.602 2.095 2.622m10.744 1.193c.036 1.055-1.193 1.93-2.715 1.95c-1.53.034-2.769-.82-2.786-1.86c0-1.065 1.202-1.932 2.733-1.958c1.522-.03 2.768.818 2.768 1.868m10.555-.405c.182 1.03-.875 2.088-2.387 2.37c-1.485.271-2.861-.365-3.05-1.386c-.184-1.056.893-2.114 2.376-2.387c1.514-.263 2.868.356 3.061 1.403"
					/></svg
				></a
			>
		</div>
	</nav>
</footer>
