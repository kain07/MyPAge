<script>
  import Logo from './Logo.svelte'
  import Nav from './Nav.svelte'

  export let segment
</script>

<style>
  header {
    display: flex;
    margin: 0 auto;
    max-width: 1400px;
    padding: 2em;
    width: 90%;

  }

  @media screen and (max-width: 767px) {
    header {
      display: block;
      
    }
  }
</style>

<header>
  <Logo />
  <Nav {segment} />
</header>
