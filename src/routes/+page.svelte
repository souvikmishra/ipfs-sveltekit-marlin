<script>
	import marlinLogo from '$lib/images/marlin_logo.png';
</script>

<main
	class="h-screen w-full overflow-hidden bg-[url($lib/images/393_Cover.png)] bg-cover bg-right-top bg-no-repeat sm:bg-[url($lib/images/640_Cover.png)] lg:bg-[url($lib/images/1280_Cover.png)] lg:bg-right xl:bg-[url($lib/images/1440_Cover.png)] 2xl:bg-[url($lib/images/1920_Cover.png)]"
>
	<div class=" mx-auto flex w-full max-w-[1920px] items-start px-5 py-6 lg:pl-16">
		<a href="https://www.marlin.org/"
			><img class="h-6 lg:h-7" src={marlinLogo} alt="Marlin Logo" /></a
		>
	</div>
	<div
		class="mx-auto flex h-full w-full max-w-[1920px] flex-col justify-start px-4 pt-12 sm:py-10 lg:ml-0 lg:mr-auto lg:w-1/2 lg:items-start lg:justify-center lg:pl-16"
	>
		<div class="flex flex-col items-center gap-8 lg:items-start">
			<h1
				class="text-balance text-center text-4xl font-semibold text-black md:text-5xl lg:text-left lg:text-6xl"
			>
				Trustless coprocessors <br />
				<span class="text-blue-700"> for limitless compute</span>
			</h1>
		</div>
		<div
			class="mb-48 flex w-full flex-col flex-wrap items-center justify-center gap-4 pt-8 md:flex-row lg:justify-start"
		>
			<a
				href="https://twitter.com/intent/follow?original_referer=https://publish.twitter.com/&region=follow_link&screen_name=MarlinProtocol"
				target="_blank"
				data-show-count="false"
				class="w-60 rounded-lg border border-blue-700 bg-white/50 px-4 py-2 text-center text-blue-700 shadow-sm transition-all duration-300 ease-in-out hover:bg-white/70 hover:shadow-lg md:w-auto"
				>Follow us on X</a
			>
			<a
				href="https://www.marlin.org/"
				target="_blank"
				class="w-60 rounded-lg bg-blue-700 px-4 py-2 text-center text-[#F2F2F9] shadow-lg transition-all duration-300 ease-in-out hover:bg-blue-800 hover:text-white hover:shadow-xl md:w-auto"
			>
				Visit marlin.org</a
			>
		</div>
	</div>
</main>
