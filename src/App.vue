<template>
  <div>
    <UserHeader/>
    <router-view/>
    <UserFooter/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
*{
  font-family: 'Montserrat', sans-serif;
}
a:hover{
	text-decoration: none;
	color: #FFD700;
  transition: 1s all;
}
.gold-text{
  color: #FFD700 !important;
}

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