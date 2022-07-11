<script lang="ts">
	import classNames from 'classnames'

	const h2Classes = 'font-bold text-[28px] md:text-4xl leading-[26.77px] md:leading-[36.42px]'
</script>

<h2 class={classNames(h2Classes, $$props.class)} {...$$restProps}>
	<slot />
</h2>
