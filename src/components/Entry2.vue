<template>
  <div>
    <div>
      <AdminSidebar />
    </div>
    <div class="main">
      <Result />
    </div>
  </div>
</template>

<script>
import AdminSidebar from "@/components/AdminSidebar.vue";
import Result from "@/views/Result.vue";
export default {
  name: "home",
  components: {
    AdminSidebar,
    Result
  }
};
</script>

<style scoped>
.main {
  margin-left: 300px;
  padding: 80px 70px 50px 70px;
}
</style>
