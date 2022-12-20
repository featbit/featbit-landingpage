<script setup>

defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="video-layout">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/FtTGhVnjReY" title="YouTube video player"
      frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen></iframe>
  </div>
</template>

<style scoped>
.video-layout {
  margin-left: auto;
  margin-right: auto;
  width: 560px;
}

@media (min-width: 1024px) {

  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
