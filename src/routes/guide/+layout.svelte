<script>
	import { page } from '$app/stores';
</script>

<div class="drawer lg:drawer-open">
	<input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content flex flex-col">
		<slot />
		<label for="my-drawer-2" class="btn btn-ghost drawer-button lg:hidden">Pages</label>
	</div>
	<div class="drawer-side border border-base-300">
		<label for="my-drawer-2" aria-label="close sidebar" class="drawer-overlay"></label>
		<ul class="menu menu-md bg-base-200 rounded-lg w-full h-full">
			<li>
				<h2 class="menu-title">SECTIONS</h2>
				<ul>
					<li>
						<a href="/guide/installation">
							<svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4" viewBox="0 0 36 36"
								><path
									fill="currentColor"
									d="M30.92 8h-4.37a1 1 0 0 0 0 2H31v20H5V10h4.38a1 1 0 0 0 0-2h-4.3A2 2 0 0 0 3 10v20a2 2 0 0 0 2.08 2h25.84A2 2 0 0 0 33 30V10a2 2 0 0 0-2.08-2"
									class="clr-i-outline clr-i-outline-path-1"
								/><path
									fill="currentColor"
									d="m10.3 18.87l7 6.89a1 1 0 0 0 1.4 0l7-6.89a1 1 0 0 0-1.4-1.43L19 22.65V4a1 1 0 0 0-2 0v18.65l-5.3-5.21a1 1 0 0 0-1.4 1.43"
									class="clr-i-outline clr-i-outline-path-2"
								/><path fill="none" d="M0 0h36v36H0z" /></svg
							>
							Installation
						</a>
					</li>
				</ul>
			</li>
		</ul>
	</div>
</div>
