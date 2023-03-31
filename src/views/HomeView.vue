<template>
  <div class="home">
    <img alt="BALG Cyber Temple Image" src="../assets/BALG_Cyber-Temple.jpg" />
    <HelloWorld msg="Coventry Grove Builders Association Presents..." />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {
    HelloWorld,
  },
});
</script>

<style>
img {
  max-width: 100%;
  height: auto;
}
.home {
  background-color: #0d022f;
}
</style>
