<template>
  <v-app>
    <v-container fluid class="fill-height">
      <v-row no-gutters>
        <v-col cols="12" sm="6">
          <form>
            <v-text-field
              :counter="10"
              label="Name"
              required
            ></v-text-field>

            <v-text-field
              label="E-mail"
              required
            ></v-text-field>

            <v-checkbox
              label="Do you agree?"
              required
            ></v-checkbox>

            <v-btn class="me-4"> submit </v-btn>
            <v-btn> clear </v-btn>
          </form>
        </v-col>
        <v-col cols="12" sm="6" class="bg-deep-purple-darken-3">
          <div>2</div>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>
<script setup>
</script>
