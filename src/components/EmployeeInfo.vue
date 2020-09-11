<template>
  <div>
    <v-form>
      <v-container>
        <div class="text-h6">Personal Details</div>

        <v-row>
          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="First Name" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Last Name" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="DOB" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Email" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Visa Type" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Visa Status" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Visa Expiry Date" filled readonly></v-text-field>
          </v-col>
        </v-row>
        <div class="text-h6">Project 1</div>

        <v-row>
          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Client 1" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Project 1" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Billing Rate" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Start Date" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="% Allocation" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="LCA Wage" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Location" filled readonly></v-text-field>
          </v-col>
        </v-row>
        <div class="text-h6">Project 2</div>

        <v-row>
          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Client 2" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Project 2" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Billing Rate" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Start Date" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="% Allocation" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="LCA Wage" filled readonly></v-text-field>
          </v-col>

          <v-col cols="12" sm="6" lg="3">
            <v-text-field value label="Location" filled readonly></v-text-field>
          </v-col>
        </v-row>
        <div class="text-right">
          <v-btn class="mr-12 mb-2" large disabled tile outlined color="success">
            <v-icon left>mdi-pencil</v-icon>Edit
          </v-btn>
        </div>
      </v-container>
    </v-form>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
</style>