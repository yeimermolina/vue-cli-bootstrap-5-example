<template>
  <div>
    <div ref="alertExample" class="alert alert-warning alert-dismissible fade show" role="alert">
      <strong>Holy guacamole!</strong> You should check in on some of those fields below.
      <button type="button" class="btn-close" @click="alert.close()" aria-label="Close"></button>
    </div>
  </div>
</template>

<script>
import { Alert } from 'bootstrap'
export default {
  name: 'Alert',
  data (){
    return {
      alert: null
    }
  },
  mounted() {
    this.alert = new Alert(this.$refs.alertExample)
  }
}
</script>

<style>

</style>