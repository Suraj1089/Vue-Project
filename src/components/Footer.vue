
<template>
  <div class="w-100 bg-pink-800 text-white">
      <h4 class="text-center py-5">Sharmila S © {{ currentYear }}</h4>
  </div>
</template>

<script>
export default {
    name: 'FooterComp',
    data() {
        return {
            currentYear: new Date().getFullYear()
        }
    }
}
</script>

<style>
</style>