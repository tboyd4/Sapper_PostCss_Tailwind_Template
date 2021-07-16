<script>
</script>

<main>
  <slot />
</main>

<style global lang="postcss">
  @import '../assets/global.pcss';
  main {
    position: relative;
    max-width: 56em;
    background-color: white;
    padding: 2em;
    margin: 0 auto;
    box-sizing: border-box;
  }
</style>
