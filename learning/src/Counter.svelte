<script>
	let count = 0;
	const decrementCount = () => {
		count--;
	}

	const incrementCount = () => {
		count++;
	}

	const resetCount = () => {
		count = 0
	}
</script>

<h1>Count: {count}</h1>
<button on:click={decrementCount}>-1</button>
<button on:click={resetCount}>Reset</button>
<button on:click={incrementCount}>+1</button>
