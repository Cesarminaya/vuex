<template>
  <div class="bg-dark text-white">
    <div class="container pt-5">
      <h1 class="pt-5 text-center text-uppercase">
        Número del componente padre: {{ $store.state.number }}
      </h1>
      <br />
      <button class="btn btn-primary" @click="$store.commit('aumentar')">
        <b>+</b>
      </button>
      <br />
      <br />
      <div>
        <SonComponent />
      </div>
    </div>
  </div>
</template>

<script>
import SonComponent from "./SonComponent.vue";
export default {
  name: "HelloWorld",
  components: {
    SonComponent,
  },
  props: {
    SonComponent,
  },
};
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
