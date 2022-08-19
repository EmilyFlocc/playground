<template>
  <div class="test">
    <h1>Playground home page</h1>
    <List :posts="posts" />
  </div>
</template>

<script>
export default {
  data:() =>({
    posts: []
  }),
  mounted() {
    this.posts = [
      { title: 'test1', id: 1 },
      { title: 'test2', id: 2 },
    ];
  },
};
</script>
