<template>
  <v-app>
    <p>{{ message }}</p>
    <v-alert
            :value="true"
            type="success"
    >
      This is a success alert.
    </v-alert>
    <div>
      <v-btn color="success">Success</v-btn>
      <v-btn color="error">Error</v-btn>
      <v-btn color="warning">Warning</v-btn>
      <v-btn color="info">Info</v-btn>
    </div>
    <p>ほげほげ</p>
  </v-app>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
