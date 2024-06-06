<div class="bg-base-200 h-full">
	<div class="m-2 p-5 bg-base-100 h-full">
		<a href="#installation" class="text-3xl" id="installation"
			><span class="link pr-2">#</span>Installation</a
		>

		<div class="my-2 py-6">
			Calcagebra is compiled in the form of a single binary at release. To install calcagebra all
			you need to do is download the binary for the desired OS and make sure it is in path. To
			download the latest binary for your operating system, run the following command in your
			terminal:

			<div class="my-2 py-6">
				<div role="tablist" class="tabs tabs-bordered bg-base-200 rounded-lg">
					<input type="radio" name="my_tabs_2" role="tab" class="tab" aria-label="Windows" />
					<div role="tabpanel" class="tab-content bg-base-100 border-base-300 rounded-box p-6">
						$URL =
						"https://github.com/megatank58/calcagebra/releases/latest/download/calcagebra.exe" $FILE
						= "calcagebra.exe" Invoke-WebRequest $URL -OutFile $FILE
					</div>

					<input type="radio" name="my_tabs_2" role="tab" class="tab" aria-label="Mac" />
					<div role="tabpanel" class="tab-content bg-base-100 border-base-300 rounded-box p-6">
						<span inert class="pr-2">$</span>curl --proto '=https' --tlsv1.2 -sSf
						https://github.com/megatank58/calcagebra/releases/latest/download/calcagebra-darwin -o
						calcagebra
					</div>

					<input type="radio" name="my_tabs_2" role="tab" class="tab" aria-label="Linux" checked />
					<div role="tabpanel" class="tab-content bg-base-100 border-base-300 rounded-box p-6">
						<span inert class="pr-2">$</span>curl --proto '=https' --tlsv1.2 -sSf
						https://github.com/megatank58/calcagebra/releases/latest/download/calcagebra-darwin -o
						calcagebra
					</div>
				</div>
			</div>

			<span class="my-2 py-6"
				>Next you need to add the binary to your path. After doing so we can move to the next stage
				where we learn how to use calcagebra.</span
			>
		</div>
		<div class="divider"></div>
			<div class="ml-auto float-right">
				<a href="/guide/variables-and-functions" class="link link-neutral"
					>Variables and Functions →</a
				>
			</div>
	</div>
</div>
