<script lang="ts">
	import classNames from 'classnames'

	const pClasses = 'text-xl leading-[19.12px] opacity-50'
</script>

<h1 class={classNames(pClasses, $$props.class)} {...$$restProps}>
	<slot />
</h1>
