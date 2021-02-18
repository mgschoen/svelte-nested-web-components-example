<script>
  export let color = "#aaffaa";
</script>

<svelte:options tag="nested-component" />
<div class="square" style="background: {color};" />

<style>
  .square {
    width: 100px;
    height: 100px;
    margin: 10px;
  }
</style>
