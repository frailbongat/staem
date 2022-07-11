<script lang="ts">
	import classNames from 'classnames'

	const h3Classes = 'font-semibold text-[28px] leading-[26.77px]'
</script>

<h3 class={classNames(h3Classes, $$props.class)} {...$$restProps}>
	<slot />
</h3>
