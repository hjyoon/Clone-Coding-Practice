<template>
  <b-row class="justify-content-center">
    <b-card
      :title="item.title"
      :img-src="item.image_url"
      img-alt="Image"
      img-top
      tag="article"
      style="max-width: 20rem"
      class="mb-3 mt-3"
    >
      <b-card-text>
        {{ item.content }}
      </b-card-text>
      <b-button href="#" variant="primary">Button</b-button>
    </b-card>
  </b-row>
</template>

<script>
export default {
  name: "PostCard",
  props: {
    item: Object,
  },
  components: {},
  data: function () {
    return {};
  },
  methods: {},
};
</script>

<style></style>
