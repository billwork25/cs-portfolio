<script>
  let count = $state(0)
  const increment = () => {
    count += 10
  }
</script>

<button onclick={increment}>
  you have ${count}
</button>
