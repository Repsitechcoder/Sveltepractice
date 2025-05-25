<script lang="ts">
 function greet() {
   alert('Welcome to Svelte!');
}
</script>

<button on:click={greet}>click me</button>

<style>
   button {
      font-size: 2em;
 }
</style>
