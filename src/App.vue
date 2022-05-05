<template>
  <div>
    <the-header></the-header>
    <badge-list></badge-list>
  </div>
</template>

<script>
import TheHeader from "./components/TheHeader.vue";
import BadgeList from "./components/BadgeList.vue";
export default {
  components: {
    TheHeader,
    BadgeList,
  },
};
</script>

<style>
html {
  font-family: sans-serif;
}
body {
  margin: 0;
}
</style>