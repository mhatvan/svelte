<script>
	function handleTouchstart() {
		// ...
	}

	function handleClick() {
		// ...
	}
</script>

<button on:click|passive="{handleClick}" on:keyup="{handleClick}"></button>
<div on:touchstart|passive="{handleTouchstart}"></div>
