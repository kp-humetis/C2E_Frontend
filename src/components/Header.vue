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
        <v-col align="center">
          <div class="text-h5">HuMetis Group</div>
          <div class="text-h7">We are Transforming</div>
          <div class="text-h7">From Consultancy to Company & From Consultants to Employees</div>
        </v-col>
      </v-row>
      <v-card class="mx-auto mb-3" max-width="720">
        <v-card-text>
          <div class="text-h8 text--primary">
            Please go through the new Proposed Salaried Options for you to opt in one of the options
            You can also see the comparison and benefits of the proposed option than your current hourly payment option
          </div>
        </v-card-text>
      </v-card>
      <v-row justify="center">
        <v-col align="center">
          <v-divider width="800"></v-divider>
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