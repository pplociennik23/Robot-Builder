<template>
  <div class="home">
    <div>
      <img class="robot" alt="robot" src="../../assets/robot-home.png" aria-hidden="true">
    </div>
    <div>
      <router-link to="/build">Get started</router-link> building your first robot!
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.home{
  text-align: center;
}
.robot{
  height: 300px;
}
</style>
