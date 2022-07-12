<script lang="ts">
	import classNames from 'classnames'

	const labelClasses = 'text-base leading-[15.3px]'
</script>

<h1 class={classNames(labelClasses, $$props.class)} {...$$restProps}>
	<slot />
</h1>
