<template>
  <div class="container">
    <div class="podcasts-agenda">
      <PodcastsPrincipal />
      <AgendaPrincipal />
    </div>
  </div>
</template>

<style>
.podcasts-agenda {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-between;
  margin: 20px 0 20px 0;
}

@media (max-width: 912px) {
  .podcasts-agenda {
    flex-direction: column;
  }
}
</style>

<script>
import PodcastsPrincipal from "./principalComponents/PodcastsPrincipal.vue";
import AgendaPrincipal from "./principalComponents/AgendaPrincipal.vue";

export default {
  name: "PodcastsAgenda",
  components: {
    PodcastsPrincipal,
    AgendaPrincipal,
  },
};
</script>