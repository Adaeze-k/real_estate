<template>
  <div >
      <div class="intro">
        <div class="container text-center search-holder py-5">
          <h1 class="font-weight-bold">Billionaire Realtors</h1>
          <div class="my-3">
            <button @click="filterType='house'" type="button" :class="{active : filterType=='house'}"  class="btn btn-outline-warning px-5 me-1">Houses</button>
            <button @click="filterType='land'" type="button" :class="{active : filterType=='land'}"  class="btn btn-outline-warning px-5 mx-1">Lands</button>
            <button @click="filterType='jv'" type="button" :class="{active : filterType=='jv'}" class="btn btn-outline-warning px-5 ms-1">JV</button>
          </div>
          
          <div v-if="filterType=='house'">
              <div class="search-holder col-md-8 offset-md-2">
              <div class="input-group mb-3">
                <select class="form-control">
                  <option>Location </option>
                  <option value="Abuja">Abuja</option>
                  <option value="Lagos">Lagos</option>
                  <option value="London">London</option>
                  <option value="Atlanta">Atlanta</option>
                </select>
                
                <select class="form-control">
                  <option>Type</option>
                  <option value="Flat">Flat</option>
                  <option value="Fully Detatched">Fully Detatched</option>
                  <option value="Duplex">Duplex</option>
                  <option value="Semi Detatched">Semi Detatched</option>
                  <option value="Terrace Apartment">Terrace Apartment</option>
                  <option value="Bungalow">Bungalow</option>
                </select>
                <select class="form-control">
                  <option>Room</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                  <option value="4">4</option>
                  <option value="5">5</option>
                  <option value="6">6</option>
                </select>
                <select class="form-control">
                  
                  <option value="Rent">Rent</option>
                  <option value="Buy">Buy</option>
                  
                </select>
                
                <button class="btn btn-orange font-weight-bold" type="button" id="button-addon2">Find Property</button>
              </div>
            </div>            
          </div>
          <div v-if="filterType=='land'">
              <div class="search-holder col-md-8 offset-md-2">
              <div class="input-group mb-3">
                <select class="form-control">
                  <option>Location </option>
                  <option value="Abuja">Abuja</option>
                  <option value="Lagos">Lagos</option>
                  <option value="London">London</option>
                  <option value="Atlanta">Atlanta</option>
                </select>
                <select class="form-control">
                  <option>Purpose</option>
                  <option value="Residential">Residential</option>
                  <option value="Commercial">Commercial</option>
                  <option value="Multipurpose">Multipurpose</option>
                  <option value="Estate Plot">Estate Plot</option>
                  
                </select>
                <select class="form-control">
                  <option>Density</option>
                  <option value="High">High</option>
                  <option value="Low">Low</option>
                  <option value="Medium">Medium</option>
                  
                </select>
                
                
                <input type="text" class="form-control" placeholder="Search Keyword" aria-label="Server">
                <button class="btn btn-orange font-weight-bold" type="button" id="button-addon2">Find Property</button>
              </div>
            </div>            
          </div>
          <div v-if="filterType=='jv'">
              <div class="search-holder col-md-8 offset-md-2">
              <div class="input-group mb-3">
                <select class="form-control">
                  <option>Location </option>
                  <option value="Abuja">Abuja</option>
                  <option value="Lagos">Lagos</option>
                  <option value="London">London</option>
                  <option value="Atlanta">Atlanta</option>
                </select>
                
                <input type="text" class="form-control" placeholder="Search Keyword" aria-label="Server">
                <button class="btn btn-orange font-weight-bold" type="button" id="button-addon2">Find Property</button>
              </div>
            </div>            
          </div>
        </div>
      </div>
      <div class="container">
        <div class="section-title p-2 my-3">
          Features Properties
        </div>
        <div class="row">
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          
        </div>
        <div class="section-title p-2 my-3">
          Latest Properties
        </div>
        <div class="row ">
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 1 Bedroom Apartment</h6>
                <h6 class="title">
                  <i class="fas fa-map-marker-alt me-2"></i>Benin-Sapele Road, Benin City, Edo State...
                </h6>
                <div class="d-flex justify-content-between fw-bold my-3 purple-text">
                  <h6 class="font-weight-bold">&#8358; 100,444,444 
                  </h6>
                  <h6 class="font-weight-bold">
                   
                    <span class="me-3"><i class="fab fa-whatsapp"></i></span> <span class="me-3"><i class="fas fa-phone-alt"></i></span>
                   
                  </h6>
                </div>
                <router-link to="/view-property">
                <div class="d-grid gap-2">
                  
                    <button class="btn btn-orange  btn-sm">Full Details </button>
                  
                </div>
                </router-link>
                
              </div>
              
              
            
            </div>
          </div>
        </div>
        <div class="text-center mb-3">
          <button class="btn btn-orange btn-lg">All Properties</button>
        </div>
         <div class="section-title p-2 my-3">
            Browse Our Top Cities
        </div>
         <div class="row">
          <div class="col-md-4  mb-4">
            <div class="shadow city">
              <div class="city-div">
                <h1>Aba</h1>
                <h5>1000+ Listings</h5>
              </div>
            </div>
          </div>
          <div class="col-md-4  mb-4">
            <div class="shadow city">
              <div class="city-div">
                <h1>Aba</h1>
                <h5>1000+ Listings</h5>
              </div>
            </div>
          </div>
          <div class="col-md-4  mb-4">
            <div class="shadow city">
              <div class="city-div">
                <h1>Aba</h1>
                <h5>1000+ Listings</h5>
              </div>
            </div>
          </div>
         </div>
      </div>
      
  </div>
</template>

<style scoped>
.intro{
  /*background: linear-gradient(to right bottom, rgb(56, 0, 100) 50%, rgb(255, 215, 0));*/
  background: linear-gradient(rgba(56, 0, 100,0.5), rgba(56, 0, 100,0.5)), url(../assets/bg1.jpg) no-repeat no-repeat center center;
  min-height: 50vh;
  padding-top: 20vh;
  padding-bottom: 10vh;
  color: #fff;
  background-attachment: fixed;
}
.search-holder{
  background: linear-gradient(rgba(56, 0, 100,0.7), rgba(56, 0, 100,0.7));

}
.city{
/*background: linear-gradient(to right bottom, rgb(56, 0, 100) 50%, rgb(255, 215, 0));*/
  background: linear-gradient(rgba(56, 0, 100,0.3), rgba(56, 0, 100,0.3)), url(../assets/bg1.jpg) no-repeat no-repeat center center;
  height: 30vh;
  position: relative;
  
}
.city-div{
  position: absolute;
  bottom: 10%;
  padding: 20px;
  width: 100%;
  background: linear-gradient(rgba(56, 0, 100,0.7), rgba(56, 0, 100,0.7));
  color: #fff;
}


</style>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
   
  },
  data(){
    return{
      filterType : 'house'
    }
  }
}
</script>
