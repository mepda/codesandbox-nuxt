<template>
  <section>
    <div class="Main__Container">
      <Login />
    </div>
  </section>
</template>

<script>
import Login from "@/components/Login";
export default {
  components: {
    Login,
  },
};
</script>

<style scoped>
.Main__Container {
  width: 100vw;
  height: 100vh;
}
</style>
