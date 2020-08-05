<template>
  <div class="container-bg">
    <Sidebar />
  </div>
</template>

<script>
import Sidebar from "./Sidebar/Sidebar.vue";
export default {
  components: {
    Sidebar,
  },
};
</script>

<style scoped>
.container-bg {
  font-family: "Anton", Arial, Helvetica, sans-serif;
  font-size: 1rem;
  letter-spacing: 1px;
  color: #322f42;
  width: 100%;
  min-height: 100vh;
  background: url("../assets/app_bg.jpg") center center;
  background-size: cover;
  overflow: hidden;
}
</style>
