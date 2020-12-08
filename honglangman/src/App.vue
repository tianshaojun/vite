<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1 class="name">jspang.com</h1>
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
  </div>
</template>

<script lang="ts">
import HelloWorld from "/@/components/HelloWorld.vue";
const jspang: string = "jspang.com";
import "/@/assets/app.css";
import data from "/@/assets/jspang.json";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  mounted() {
    console.log(jspang);
    console.log(data.name);
    console.log(data.website);
  },
};
</script>

<style lang="scss">
.name {
  color: green;
}
</style>>
