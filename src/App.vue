<template>
  <div id="app">
    <app-button @click="log">
      <hart-icon />
      add to favorites
    </app-button>
  </div>
</template>

<script>
import AppButton from "./components/AppButton.vue";
import HartIcon from "./components/HartIcon.vue";

export default {
  components: {
    AppButton,
    HartIcon
  },
  methods: {
    log() {
      console.log('works');
    }
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>

