<template>
  <div>
    <!-- <p> My Series Page </p> -->
    <iframe width="96%" height="615"  
      src="https://www.youtube.com/embed/Q6iK6DjV_iE" 
      frameborder="0" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
      allowfullscreen>
    </iframe>
    <DescriptionCard></DescriptionCard>
  </div>  
</template>

<script>
import DescriptionCard from "./components/DescriptionCard.vue";
export default {
  name: "ShowPage",
  data() {
    return {
    }
  },
  components: {
    DescriptionCard,
  }
}
</script>

<style>
  p {
    color: black;
  }
</style>
