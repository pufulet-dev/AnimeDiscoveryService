<template>
  <div id="moreAnime">
    <span class="text">
      <h1>Looking for more anime?</h1>
      <h3>Browse the rest of our catalog!</h3>
    </span>
    <!-- <img src="https://coverfiles.alphacoders.com/538/53840.png" class="banner"> -->
    <router-link to="/browse" class="buttonMA"> <p> Browse </p> </router-link>
  </div>
</template>

<script>
export default {
  name: "MoreAnime",
  data() {
    return {
    }
  }
}
</script>

<style>
  #moreAnime {
    line-height: 50px;
  }
  .text {
    color: black;
    font-family: 'Comfortaa', cursive;
  }
  .text h1 {
    font-size: 40px;
  }
  .text h3 {
    font-size: 30px;
  }
  .buttonMA {
    /* text-decoration: none; */
    color: black;
    background-color: black;
  }
  .buttonMA:hover {
    color:  #ea2d2e;
    box-shadow: 0 12px 16px 0 black, 0 12px 16px 0 black;
    background-color: transparent;
    transition: all 0.3s ease 0s;
  }
</style>
