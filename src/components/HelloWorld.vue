<template>
  <div class="hello">
    <p>---</p>
    <h5>{{ msg }}</h5>
    <h1>Our Beneficently Ambient Learning Guild</h1>
    <h5>
      We are an Ideologically Organized Association of Developers Dedicated To
      Deliverables Because...
    </h5>
    <h1>Our Bountiful Activity Legitimizes Growing</h1>
    <h5>We Seek To Always Improve, Knowing...</h5>
    <h1>Our Betterment Awakens Liberations Greater</h1>
    <h5>
      For All And So We Combine Our Intentions and Through This Establish...
    </h5>
    <h1>Our Builders Association ov Layered Generalists</h1>
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
.hello {
  background-color: #0d022f;
}
h3 {
  margin: 40px;
}
h1 {
  margin: 40px;
  color: #a915a1;
}
h5 {
  margin: 40px;
  color: #10598a;
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
