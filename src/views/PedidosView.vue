<template>
  <div>
    <div class="main-container">
      <h1>Gerenciar pedidos: </h1>
      <DashboardVue />
    </div>
  </div>
</template>

<script>
import DashboardVue from '@/components/Dashboard.vue';

export default {
  name: "Pedidos",
  components: {
    DashboardVue
  }
}
</script>
