<script lang="ts">
	import classNames from 'classnames'

	const displayClasses = 'font-bold text-[40px] md:text-5xl leading-[38.24px] md:leading-[45.89px]'
</script>

<p class={classNames(displayClasses, $$props.class)} {...$$restProps}>
	<slot />
</p>
