<template>
  <div>
    <Header></Header>
    <EmployeeInfo></EmployeeInfo>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import EmployeeInfo from "@/components/EmployeeInfo.vue";
export default {
  name: "Home",
  components: {
    Header,
    EmployeeInfo,
  },
};
</script>
