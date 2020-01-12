<template>
  <div>
    <div>
      <AdminSidebar />
    </div>
    <div class="main">
      <entries />
    </div>
  </div>
</template>

<script>
import AdminSidebar from "@/components/AdminSidebar.vue";
import entries from "@/views/entries.vue";
export default {
  name: "home",
  components: {
    AdminSidebar,
    entries
  }
};
</script>

<style scoped>
.main {
  margin-left: 300px;
  padding: 80px 70px 50px 70px;
}
</style>
