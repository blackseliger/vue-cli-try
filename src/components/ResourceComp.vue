<template>
  <div>
    {{ resource }}
  </div>
</template>

<script>
export default {
  name: "resource-comp",
  computed: {
    resource() {
      return this.$store.getters["resource"]
    },
  },
}
</script>

<style scoped>
div {
  font-family: 'Brush Script MT', cursive;
  font-size: 14pt;
}
</style>