<svelte:options tag="interactive-component" />
<div class="wrapper">
  <nested-component color="#ff0000" />
  <nested-component color="#0000ff" />
  <nested-component />
</div>

<style>
  .wrapper {
    display: flex;
    background: orange;
  }
</style>
