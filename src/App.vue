<template>
  <div class="main">
    <h1>Project App</h1>
      <img :src="require('./logo.png')" alt="logo" />
    <Content />
  </div>
</template>

<script>
import Content from "@v2b/Content"
export default {
  components: {
    Content
  },
};
</script>

<style scoped lang="scss">
.main {
  img {
    width: 200px;
  }

  h1 {
    font-family: Arial, Helvetica, sans-serif;
    font-size:60px;
  }
}
</style>
