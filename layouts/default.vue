<template>
  <div class="container">
    <TheHeader />
    <nuxt />
  </div>
</template>
<script>
import TheHeader from "@/components/Navigation/TheHeader";
export default {
  components: {
    TheHeader
  }
};
</script>
<style lang="scss">
* {
  box-sizing: border-box;
}

html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  font-family: "Montserrat", sans-serif;
}
.container {
  max-width: 59.6875rem;
  margin-left: auto;
  margin-right: auto;
  min-height: 100%;
}
</style>
