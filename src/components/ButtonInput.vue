<template>
        <button>Valider</button>
</template>
<script>
export default {
  name: "ButtonInput",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
  .main-container {
    display: flex;
    justify-content: space-evenly;
  }
</style>
