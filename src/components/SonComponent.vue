<template>
  <div class="bg-success">
    <h1 class="text-center py-5 text-uppercase">
      Numero del componente Hijo {{ $store.state.number }}
    </h1>
  </div>
</template>

<script>
export default {
  name: "SonComponent",
  data() {
    return {};
  },
};
</script>

<style>
</style>