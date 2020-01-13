<template>
  <div>
    <div>
      <AdminSidebar />
    </div>
    <div class="main">
      <History />
    </div>
  </div>
</template>

<script>
import AdminSidebar from "@/components/AdminSidebar.vue";
import History from "@/components/History.vue";
export default {
  name: "home",
  components: {
    AdminSidebar,
    History
  }
};
</script>

<style scoped>
.main {
  margin-left: 300px;
  padding: 80px 70px 50px 70px;
}
</style>
