<template>
  <header>
    <h1>{{ title }}</h1>
    <Button color="green" title="Add"></Button>
  </header>
</template>

<script>
import Button from "./Button";

export default {
  name: "Header",
  props: {
    title: {
      type: String,
    },
  },

  components: {
    Button,
  },


};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
