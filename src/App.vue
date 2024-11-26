<script setup>
import AwesomeAlert from './components/AwesomeAlert.vue';
</script>

<template>
  <AwesomeAlert  heading="Awesome Alert" message="This is Fantastic!" color="red" />
  <awesome-alert heading="It's Dynamic" message="You can pass anything in props" color="green" />
  <awesome-alert heading="Upload Failed!" message="File cannot be more than 5MB" color="red" />
  <awesome-alert heading="Operation successful!" message="Email has been successfully sent" color="green" />
</template>

<style scoped>
</style>
