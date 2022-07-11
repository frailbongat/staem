<script lang="ts">
	import classNames from 'classnames'

	const h1Classes = 'font-bold text-[40px] leading-[38.24px]'
</script>

<h1 class={classNames(h1Classes, $$props.class)} {...$$restProps}>
	<slot />
</h1>
