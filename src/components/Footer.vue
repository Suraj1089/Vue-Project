<template>
  <div class="w-100 bg-pink-800 text-white" style="margin-top: 20px;">
      <h4 class="text-center py-5">suraj@ {{ currentYear }} </h4>
  </div>
</template>

<script>
export default {
    name: 'FooterComp',
    data() {
      return {
        currentYear:new Date().getFullYear(),
      }
    },
    methods: {
      
    }
}
</script>

<style>
</style>
