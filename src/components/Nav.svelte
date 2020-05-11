<script>
	export let segment;
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400,700');
nav {
    align-items: flex-end;
    display: flex;
    flex: 1;
    font-family: 'Open Sans', sans-serif;
    font-weight: 700;
    justify-content: flex-end;
    text-transform: uppercase;
  }

  a {
    color: inherit;
    text-decoration: none;
    padding: 10px 5px;
    display: block;
    position: relative;
    margin-left: 20px;
  }

  a:not(.selected) {
    opacity: 0.7;
  }

  a::before {
    content: '';
    position: absolute;
    transition: transform .3s ease;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 2px;
    background: #bbe1fa;
    transform: scaleX(0);
  }

  a:hover::before,
  .selected::before {
    transform: scaleX(1);
  }

  .selected::before {
    background: #0F4C75;
  }
</style>

<nav>
  <a class='{segment === undefined ? "selected" : ""}' href='.'>Inicio</a>
  <a class='{segment === "Productos" ? "selected" : ""}' href='Productos'>Productos</a>
  <a class='{segment === "Servicios" ? "selected" : ""}' href='Servicios'>Servicios</a>
  <a class='{segment === "about" ? "selected" : ""}' href='about'>Acerca</a>
  <a rel=prefetch class='{segment === "blog" ? "selected" : ""}' href='blog'>Blog</a>
</nav>
