<template>
  <header>
    <strong>Verbarium</strong>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    userName: String,
  },
};
</script>

<style scoped>
header {
  color: cadetblue;
}
</style>
