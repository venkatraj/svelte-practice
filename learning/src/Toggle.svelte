<script>
  let loggedIn = false

  const toggle = () => {
    loggedIn = !loggedIn
  }
</script>

{#if !loggedIn}
<button on:click={toggle}>
  Login
</button>
{:else}
<button on:click={toggle}>
  Logout
</button>
{/if}