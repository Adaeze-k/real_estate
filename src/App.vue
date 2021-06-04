<template>
  <UserHeader/>
  <router-view/>
</template>

<style>

</style>

<script>
import UserHeader from '@/components/UserHeader.vue'
export default {
  name: 'App',
  components: {
       UserHeader
  }
}
</script>