<svelte:options tag="docure-article-card" />

<div class="docure-article-card">
  <p class="docure-article-card-title">
    <slot name="title" />
  </p>
  <div class="docure-article-card-description">
    <slot name="description" />
  </div>
</div>

<style>
  .docure-article-card {
    width: 400px;
    background: #fff;
    margin-bottom: 2rem;
    box-shadow: 0 2px 7px 2px #bfbfbf;
    padding: 14px;
  }
</style>
