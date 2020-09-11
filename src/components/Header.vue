<template>
  <div>
    <v-app-bar color="grey lighten-5">
      <v-img
        class="mx-2"
        src="https://humetis.com/library/assets/images/Humetis_Logo.png"
        max-height="50"
        max-width="50"
        contain
      ></v-img>
      <v-toolbar-title>Humetis Group</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-menu left bottom>
        <template v-slot:activator="{ on, attrs }">
          <v-btn icon v-bind="attrs" v-on="on">
            <v-icon>mdi-dots-vertical</v-icon>
          </v-btn>
        </template>

        <v-list>
          <v-list-item @click="() => {}">
            <v-list-item-title>Change Password</v-list-item-title>
          </v-list-item>
          <v-list-item @click="() => {}">
            <v-list-item-title>Logout</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>
    <v-container fluid>
      <v-row justify="center">
        <!-- <v-col align="right">
          <v-img
            src="https://humetis.com/library/assets/images/Humetis_Logo.png"
            height="50"
            width="70"
          ></v-img>
        </v-col>-->
        <v-col align="center">
          <div class="text-h5">HuMetis Group</div>
          <div class="text-h7">We are Transforming</div>
          <div class="text-h7">From Consultancy to Company & From Consultants to Employees</div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>