<template>
  <Window :title="data.title" :window="data">
    <p>
      About you, not me!!
    </p>
  </Window>
</template>

<script>
  import Window from "~/core/components/window/Window";
  export default {
    name: "WindowExample",
    components: {Window},
    props: {
      data: Object
    }
  }
</script>

<style scoped lang="scss">
  p {
    color: #AAA;
  }
</style>
