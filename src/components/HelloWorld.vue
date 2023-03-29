<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Our Beneficently Ambient Learning Guild</h2>
    <h3>
      We are an Ideologically Organized Association of Developers Dedicated To
      Deliverables Because...
    </h3>
    <p>Our Bountiful Activity Legitimizes Growing</p>
    <h3>We Seek To Always Improve, Knowing...</h3>
    <p>Our Betterment Awakens Liberations Greater</p>
    <h3>
      For All And So We Combine Our Intentions and Through This Establish...
    </h3>
    <p>Our Builders Association ov Layered Generalists</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
