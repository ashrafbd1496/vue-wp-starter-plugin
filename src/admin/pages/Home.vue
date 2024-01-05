<template>
  <div class="home">
    <span>{{ msg }}</span>
  </div>
</template>

<script>
export default {
  name: "Home",

  data() {
    return {
      msg: "Welcome to vue wordpress development"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  font-size: 40px;
  color: red;
}
</style>
