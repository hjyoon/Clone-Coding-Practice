<template>
  <div>
    <post-card v-for="item in items" :key="item.id" :item="item"></post-card>
  </div>
</template>

<script>
import { mapState } from "vuex";
import PostCard from "./PostCard.vue";

export default {
  name: "PostCardList",
  components: { PostCard },
  computed: {
    ...mapState(["items"]),
  },
};
</script>

<style></style>
