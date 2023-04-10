<template>
  <div class="myriad">
    <CoursesAnnouncement />
    <!-- <img
        alt="A Technician In A Cyberpunk Occult Style Working On An Engine"
        src="../assets/Imagine_Occult-Technician_with-stamp.jpg"
      /> -->
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import CoursesAnnouncement from "@/components/CoursesAnnouncement.vue"; // @ is an alias to /src

export default defineComponent({
  name: "CoursesView",
  components: {
    CoursesAnnouncement,
  },
});
</script>
