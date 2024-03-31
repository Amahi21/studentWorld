<template>
  <div class="header">
      <img class="logo"
           src="../images/logo.png">
    <v-btn size="small">
      Button
    </v-btn>
  </div>

</template>

<script>
export default {
  name: "Header"
}
</script>

<style>
  .header {
    width: 100%;
    height: 6%;
    background: white;
    border: 3px solid lightskyblue;
  }

  .logo {
    width: auto;
    height: 100%;
    margin-left: 50px;
  }
</style>
