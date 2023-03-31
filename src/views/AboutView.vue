<template>
  <div class="about">
    <!-- <img
      alt="A Technician In A Cyberpunk Occult Style Working On An Engine"
      src="../assets/Imagine_Occult-Technician_with-stamp.jpg"
    /> -->
    <AboutLinks />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import AboutLinks from "@/components/AboutLinks.vue"; // @ is an alias to /src
export default defineComponent({
  name: "AboutView",
  components: {
    AboutLinks,
  },
});
</script>

<style>
img {
  max-width: 100%;
  height: auto;
}
.about {
  background-color: #0d022f;
}
</style>
