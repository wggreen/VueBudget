<template>
  <v-card>
    <v-card-title class="purple--text">Annual Income</v-card-title>
    <v-card-text>
      <v-form>
        <v-text-field
          v-model="inputVal"
          type="number"
          outlined
          color="purple"
          filled
          prefix="$"
        />
      </v-form>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  props: ["annualAmount"],
};
</script>

<style>
</style>