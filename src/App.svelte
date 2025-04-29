<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
  import Title from './lib/Title.svelte'
</script>

<main>
  <Title />
  <div>
    <iframe title="Khoi" frameborder="0" src="https://itch.io/embed-upload/11784971?color=000000" allow="fullscreen" width="640" height="380"><a href="https://billm1066.itch.io/parallel-parking-practice">Play Parallel Parking Practice on itch.io</a></iframe>
  </div>
  <h1>Khoi exists probably</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">
    Click on the Vite and Svelte logos to learn more
  </p>
</main>

<style>
  .read-the-docs {
    color: #888;
  }
</style>
