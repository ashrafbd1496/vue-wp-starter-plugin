<template>
  <div class="hello">
    <span>{{ msg }}</span>
  </div>
</template>

<script>
export default {
  name: "Home",

  data() {
    return {
      msg: "Welcome to Your Vue.js Frontend App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* Style the hello div */
.hello {
  font-size: 40px;
  color: red;
}

/* Style the span within the hello div */
.hello span {
  color: #333;
  font-weight: bold;
}
</style>
