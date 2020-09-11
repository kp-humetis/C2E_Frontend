<template>
  <div>
    <Header></Header>
    <Employee></Employee>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Employee from "@/components/Employee.vue";
export default {
  name: "Home",
  components: {
    Header,
    Employee,
  },
};
</script>
