<template>
  <div>
    <v-container fluid>
      <div class="text-center">
        <v-btn class="mx-8 mb-4" depressed color="success">Select Employee</v-btn>
        <v-btn class="mx-8 mb-4" depressed color="primary">Add Employee</v-btn>
      </div>
    </v-container>
    <EmployeeInfo />
  </div>
</template>

<script>
import EmployeeInfo from "@/components/EmployeeInfo.vue";
export default {
  components: {
    EmployeeInfo,
  },
};
</script>

<style lang="scss" scoped>
</style>