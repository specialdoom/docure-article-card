<svelte:options tag="docure-article-card" />

<script>
  export let title = "";
  export let description = "";
</script>


<div class="docure-article-card">
  <p class="docure-article-card-title">{title}</p>
  <div class="docure-article-card-description">
    {description}
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

  .docure-article-card-title{
    color: #4392f1;
    font-size: 18px;
  }

  .docure-article-card-title:hover{
    text-decoration: underline;
    cursor: pointer;
  }

</style>