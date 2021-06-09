<template>
  <footer class="">
    <div class="container py-5">
		<div class="row">
			<div class="col-md-4">
				<div>
					<img src="@/assets/logo.png" class="img-fluid">
				</div>
				<p class="text-justify text-muted">
					 Our mission is to provide an outstanding level of service, excellence and expertise in the real estate market to our clients.
				</p>
			</div>
			<div class="col-md-5">
				<h5 class="gold-text pb-3 mt-sm-5">Useful Links</h5>
				<div class="row">
				
					<div class="col-6">
						<div class="">
							
							<p>
								<router-link to="/">Home</router-link>
							</p>
							<p>
								<router-link to="/">Properties</router-link>
							</p>
							<p>
								<router-link to="/">About Us</router-link>
							</p>
							
						</div>
					</div>
							
					<div class="col-6">
						<div class="">
							
							<p>
								<router-link to="/">Blog</router-link>
							</p>
						
							<p>
								<router-link to="/">Agent Login</router-link>
							</p>
							<p>
								<router-link to="/">Agent Registration</router-link>
							</p>
							
						</div>
					</div>
				</div>
				
			</div>
			
			<div class="col-md-3">
				<div class="mt-sm-5 ">
					<h5 class="gold-text  pb-3">Contact Us</h5>
					<p>
						<i class="fas fa-home me-2"></i>Billionaire Realtors suite 0017 KINGFEM GA247 Mall, Mabushi Ahmadu Bello Way.
					</p>
					<p>
						<i class="fas fa-phone me-2"></i> +234 808 111 6334
					</p>
					<p>
						<i class="fas fa-envelope me-2"></i> info@billionairerlts.com
					</p>

				</div>
			</div>
		</div>
		<hr />
		<div class="text-center py-3">
			<router-link to="/">
				<i class="fab fa-facebook fa-2x mx-5"></i>
			</router-link>
			<router-link to="/">
				<i class="fab fa-twitter fa-2x mx-5"></i>
			</router-link>
			<router-link to="/">
				<i class="fab fa-instagram fa-2x mx-5"></i>
			</router-link>
			
		</div>
	</div>
   <div class="bg-dark py-3 text-center">
	&copy; {{ new Date().getFullYear() }} Billionaire Realtors
   </div>
  </footer>
  
</template>
<style scoped>
footer{
	background: #380064;
	color: #fff;
}
footer img{
	width: 200px;
}
a{
	text-decoration: none;
	color: #fff;
}
a:hover{
	text-decoration: none;
	color: #FFD700;
}


</style>
<script>


export default {
  name: 'UserFooter',
  
}
</script>