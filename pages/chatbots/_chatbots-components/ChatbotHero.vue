<script setup lang="ts">
const runtimeConfig = useRuntimeConfig();
</script>

<template>
	<div
		class="font-Poppins text-Black container flex flex-col items-center pt-20 pb-40 md:pb-28"
	>
		<img
			src="/images/pacifiqlogo1.png"
			alt=""
			class="max-w-54 cursor-pointer transition-all hover:scale-110"
		/>
		<h3 class="my-5 mt-24 text-lg font-semibold">
			Helping Businesses Transition to AI
		</h3>
		<div class="flex flex-col items-center">
			<h1
				class="font-Poppins max-w-sm text-center text-4xl leading-snug font-bold md:text-7xl"
			>
				Advanced
			</h1>
			<span
				class="border-l-[4px] border-[#2310d0] bg-gradient-to-r from-[#1023d052] to-[#3734980a] 
            pr-[8px] pl-[8px] font-Poppins max-w-xl text-center text-5xl 
            leading-snug font-bold md:text-7xl whitespace-nowrap"
			>
				AI Text Chatbots
			</span>
		</div>
		<div
			class="mt-5 gap-3 *:my-3 *:block max-sm:w-full max-sm:*:mx-auto max-sm:*:w-full max-sm:**:w-full sm:flex"
		>
			<a
				:href="runtimeConfig.public.calendly"
				target="_blank"
			>
				<Button
					class="inline-flex items-center justify-center gap-2 shadow-lg shadow-gray-300 max-sm:w-full"
				>
					<Icon
						name="mynaui:telephone"
						size="20"
					/>
					Book A Call</Button
				>
			</a>
			<a href="#pricing">
				<Button
					is-light
					class="max-sm:mt-3 max-sm:w-full max-sm:text-start"
					>Discover Pricing</Button
				>
			</a>
		</div>
	</div>
</template>
