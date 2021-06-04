<template>
  <footer class="">
    <div class="container py-5">
		<div class="row">
			<div class="col-md-4">
				<div>
					<img src="@/assets/logo.png" class="img-fluid">
				</div>
				<p class="text-justify text-muted">
					Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magni i corporis aperiam, dolores at necessitatibus distinctio quaerat.
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
						<i class="fas fa-home me-2"></i>Billionaire Realtors , Fill the company address
					</p>
					<p>
						<i class="fas fa-phone me-2"></i> +234 810 6698 635
					</p>
					<p>
						<i class="fas fa-envelope me-2"></i> info@domainname.com
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