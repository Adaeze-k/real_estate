<template>
  <div class="top-div">
   	<nav class="navbar navbar-expand-lg navbar-dark fixed-top">
		<div class="container">
			<router-link to="/" class="navbar-brand" href="/">
				<img src="@/assets/logo.png" class="img-fluid">
			</router-link>
			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<form class="mx-auto">
					<input class="form-control form-control-sm" type="search" placeholder="Search by location, type, price etc..." aria-label="Search">
				</form>
				<ul class="navbar-nav  mb-2 mb-lg-0 navbar-nav-scroll">
					<li class="nav-item">
						<router-link to="/" exact-active-class="active" class="nav-link" aria-current="page" >Home </router-link>
					</li>
					<li class="nav-item">
						<router-link to="/"  exact-active-class="active" class="nav-link " aria-current="page" >Properties </router-link>
					</li>
					<li class="nav-item">
						<router-link to="/about"  exact-active-class="active" class="nav-link " aria-current="page" >About Us  </router-link>
					</li>
					<li class="nav-item">
						<router-link to="/"  exact-active-class="active" class="nav-link " aria-current="page">Blog </router-link>
					</li>
					<li class="nav-item">
						<router-link to="/"  exact-active-class="active" class="nav-link " aria-current="page" >Contact Us </router-link>
					</li>	
				</ul>
				
			</div>
		</div>
	</nav>
  </div>
  
</template>
<style scoped>
nav{
	background: #380064;
	color: #fff;
}
.nav-item, .nav-link{
	color: #fff !important;
	margin-right: 10px;
}
.nav-item:hover, .nav-link:hover, .active{
	color: #FFD700 !important;
}
.navbar-brand img{
	width: 70px;
}
nav form{
	width: 50%;
}
.top-div{
	margin-bottom:10vh !important
}

</style>

<script>


export default {
  name: 'UserHeader',
  
}
</script>