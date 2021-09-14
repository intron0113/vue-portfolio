<template>
  <v-col cols="12" sm="6" md="4" lg="4">
    <v-card class="mx-auto">
      <v-img
        class="white--text align-end"
        src="https://dummyimage.com/250x150/000/fff"
      >
        <v-card-title></v-card-title>
      </v-img>
      <v-card-subtitle class="pb-0"></v-card-subtitle>

      <v-card-text class="text--primary">
        <div>{{ product.category }}</div>
        <div>{{ product.use }}</div>
        <div>{{ product.info }}</div>
      </v-card-text>

      <v-card-actions>
        <v-btn clor="orange" text>
          LINK
        </v-btn>
      </v-card-actions>
    </v-card>
  </v-col>
</template>

<script>
export default {
  name: 'Product',
  props: ['product'],
};
</script>
<style></style>
