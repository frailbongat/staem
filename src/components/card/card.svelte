<script lang="ts">
	import { Display, H3, HR, P, Windows } from '$components'

	export let name: string
	export let description: string
	export let price: string
	export let image: string
</script>

<div class="rounded-[30px] overflow-hidden bg-primary-900 md:flex">
	<div class="h-[280px] md:w-[599px] bg-cover bg-center" style="background: url({image})" />

	<div
		class="p-5 space-y-[18px] md:pt-[47px] md:pr-[34px] md:pb-[35px] md:pl-[51px] md:flex md:justify-between md:space-y-0 md:grow"
	>
		<div>
			<H3>{name}</H3>
			<P class="mt-[18px] md:mt-3">{description}</P>
			<HR class="w-[127px] mt-[18px] md:mt-[25px]" />
		</div>

		<div class="flex justify-between md:flex-col md:items-end">
			<Windows />
			<Display>{price}</Display>
		</div>
	</div>
</div>
