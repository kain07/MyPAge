<script>
import { fade, fly, slide} from 'svelte/transition';
import { quintOut } from "svelte/easing";

let images = [
  "Bienvenidos-Wi-Fi.gif",
  "wordcloud_WiFi.png",
  "WLANTech-logo.png",
]

let activeIndex = 0;
setInterval(() => {
  let next = activeIndex +1;
  activeIndex = next == 3 ? 0 : next;
}, 7000);

</script>

<style>


  img {
    width: 100%;
    height: 100%;
    max-width: 1080px;
    max-height: 500px;
  }

  @media screen and (max-width: 1024px) {
    img {
      max-width: 800px;
    }
  }

</style>

<svelte:head>
  <title>WLANTechnologies</title>
</svelte:head>


<section style="display:flex;justify-content:center">
  {#each images as image, i}
    {#if activeIndex === i}
      <img
        transition:slide={{ delay: 500, duration: 300, easing: quintOut }}
        style="position:absolute"
        src={image}
        alt="Presentation" />
    {/if}
  {/each}
</section>