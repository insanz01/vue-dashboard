<template>
  <div class="hello">
    <h1>Nama saya {{nama}}</h1>
  </div>
</template>

<script>
export default {
  name: "hello",
  data() {
    return {
      nama: "Muhammad Insan Kamil"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>
