<template>
  <div class="home">
    <post-card-list></post-card-list>
  </div>
</template>

<script>
import PostCardList from "../components/PostCardList.vue";

export default {
  name: "Home",
  components: { PostCardList },
};
</script>
