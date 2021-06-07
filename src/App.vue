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
.purple-text{
  color: #380064 !important;
}
.btn-orange{
 background: #FFD700 !important;
  color: #380064 !important
}
.font-weight-bold{
  font-weight: 900;
}
.section-title{
  background-color: #380064 !important;
  color: #fff;
  font-weight: 900 !important;
}
.property-data h6{
  margin: 0;
  padding: 0;
}
.property-data .title{
  border-bottom: 1px solid  #380064;
}
.property-img{
  height: 200px;
  overflow: hidden;
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