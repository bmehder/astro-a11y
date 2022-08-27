<script>
  export let src
  export let href
  export let title
  export let author
</script>

<div class="card">
  <div class="card__image">
    <img {src} alt="" />
  </div>
  <div class="card__content">
    <h3>
      <a {href}>{@html title}</a>
    </h3>
    <p />
    <small> Author: {author} </small>
  </div>
</div>
