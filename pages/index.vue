<template>
  <div>
    <button @click="showNotification">Mostrar Notificación</button>
  </div>
</template>

<script>
export default {
  methods: {
    showNotification() {
      this.$toast('¡Motor en peligro!');
    }
  }
}
</script>

<style>
/* Tu estilo aquí */
</style>
