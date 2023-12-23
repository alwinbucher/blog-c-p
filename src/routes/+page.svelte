<script lang="ts">
  import AboutUs from './about-us/+page@.md'
  import Posts from './posts/+page@.svelte'
</script>

<img src="./boot.jpeg" alt="Our Boat" width="200" />
<h1>Janosh</h1>

<p>
  We like sailing with our cat!<br />
  Our cat likes sailing with us!
</p>

<AboutUs />

<Posts />

<style>
  img[alt='me'] {
    border-radius: 50%;
    object-fit: cover;
    height: 10em;
    width: 10em;
    margin: 4em auto 0;
  }
  h1 {
    margin: 0;
  }
  :is(h2, p) {
    text-align: center;
  }
  strong {
    text-align: center;
    color: #eee;
    margin: 2em auto 3em;
    background-color: darkcyan;
    padding: 2pt 9pt;
    border-radius: 9pt;
    max-width: 500px;
  }
  strong a {
    color: white;
    text-decoration: underline;
  }
</style>
