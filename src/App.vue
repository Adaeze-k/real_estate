<template>
  <UserHeader/>
  <router-view/>
  <UserFooter/>
</template>

<style>

</style>

<script>
import UserHeader from '@/components/UserHeader.vue'
import UserFooter from '@/components/UserFooter.vue'
export default {
  name: 'App',
  components: {
       UserHeader,
       UserFooter
  }
}



</script>