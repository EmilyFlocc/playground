<template>
  <div class="home-page">
    <h1>Playground home page</h1>
    <List :posts="posts" />
  </div>
</template>

<script setup>
let posts = ref([]);
onMounted(() => {
  posts.value = [
    { title: "test1", id: 1 },
    { title: "test2", id: 2 },
  ];
});
</script>
