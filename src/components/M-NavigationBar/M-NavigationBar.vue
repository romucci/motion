<template>
  <div id="navigation-bar">

  </div>
</template>

<script>
export default {
  props: {
    links: {
      type: Array,
      required: false
    }
  }
};
</script>

<style scoped lang="sass">
$primary-background: #3eaf7e
$primary-background__dark: #27664b

#navigation-bar
  width: 100%
  height: 80px
  background-color: $primary-background
  border-bottom: $primary-background__dark 2px solid
</style>
