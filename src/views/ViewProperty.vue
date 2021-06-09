<template>
  <div >
      <div class="intro">
        <h3>For Sale: WATERFRONT 5 BEDROOM FULLY DETACHED DUPLEX WITH SWIMMING POOL</h3>
      </div>
      <div class="container">
        <div class="slider-div">
        
            <img :src="image" class="img-fluid" @click="next"/>
        
        </div>

        <div class="row">
            <div class="col-md-8">
                <div class="shadow border card p-2 mb-3">
                    <div class="section-title p-2">
                        Property Details
                    </div>
                    <div class="d-block d-sm-flex justify-content-between mb-3">
                        <div class="btn-orange p-1 px-3">
                            <i class="fab fa-whatsapp"></i> Enquire On Whatsapp
                        </div>
                        <div class="text-center bg-light p-1">
                            <h4 class="font-weight-bold">&#8358; 100,444,444 
                        </h4>
                        </div>
                    </div>
                    <h6 class="font-weight-bold">For Sale: WATERFRONT 5 BEDROOM FULLY DETACHED DUPLEX WITH SWIMMING POOL</h6>
                    <p><i class="fas fa-map-marker-alt me-2"></i>Wuse 2 Abuja</p>
                    <p><i class="fas fa-calendar-alt me-2"></i>Added On : 20/12/2021</p>
                    <p>Category : For Sale | Type : Duplex | Status : Available | Construction Status | Developed</p>
                
                </div>
                <div class="shadow border card p-2 mb-3">
                    <div class="section-title p-2">
                        Property Full Description
                    </div>
                    <p class="py-3 text-justify text-muted">
                        WATERFRONT 5 BEDROOM FULLY DETACHED DUPLEX WITH SWIMMING POOL PRICE: N350M  <br>
                        LOCATION: OSAPA,LAGOS Features: - All Rooms Ensuite -Penthouse Masters -2terrace -Waterfront view -Luxury finishing - 1 Boy Quarter -Laundry room - Big Compound - CCTV Cameras - Jacuzzi -Bathtub - Fully Fitted Kitchen - Security Doors - Swimming Pool - Gym house -Study room
                    </p>
                
                </div>
            </div>
            <div class="col-md-4">
                <div class="shadow border card p-2 mb-3 bg-light">
                    <div class="section-title p-2">
                        Contact Details
                    </div>
                    <li class="py-2 text-justify text-muted">
                        <i class="fab fa-whatsapp"></i> Enquire On Whatsapp
                    </li>
                    <li class="py-2 text-justify text-muted">
                        <i class="fas fa-phone-alt"></i> +234 810 4491 751
                    </li>
                    <li class="py-2 text-justify text-muted">
                        <i class="fas fa-envelope"></i> info@domain.com
                    </li>
                    <li class="py-2 text-justify text-muted">
                        <i class="fas fa-map-marker-alt"></i> Company Address Full Location Head Office for Enquiry
                    </li>
                
                </div>
            </div>
        </div>
        <div class="section-title p-2 my-3">
          Related Properties
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
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3  mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3 mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3 mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3 mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3 mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
          <div class="col-md-3 mb-4">
            <div class="property-data shadow">
              <div class="property-img">
                <img src="@/assets/bg.jpg" class="img-fluid">  
              </div>
              <div class="p-2">
                <h6 class="font-weight-bold  title my-3">Luxury 2 Bedroom Apartment</h6>
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
                
                <div class="d-grid gap-2">
                  <button class="btn btn-orange  btn-sm">Full Details </button>
                </div>
                
              </div>
              
              
            
            </div>
          </div>
        </div>
        
       
      </div>
  </div>
</template>

<style scoped>
.intro{
  background: #000;
  min-height: 25vh;
  padding-top: 10vh;
  color: #fff;
  text-align: center;
}
li{
    list-style-type: square;
}
.slider-div{
    max-height: 60vh;
    overflow: hidden;
}
</style>

<script>
const images = [
  "https://source.unsplash.com/1600x900/?house",
  "https://source.unsplash.com/1600x900/?home",
  "https://source.unsplash.com/1600x900/?building"
];

export default {
    name:'ViewProperty',
    components:{
        
    },
    data(){
        return{
            
            index: 0, image: images[0] 
        }
    },
    methods: {
    next() {
      this.index = (this.index + 1) % images.length;
      this.image = images[this.index];
    },
    prev() {
      this.index = (this.index - 1) % images.length;
      this.image = images[this.index];
    },
    autoChangeSlide() {
      setInterval(() => {
        this.next();
      }, 5000);
    },
  },
  beforeMount() {
    this.autoChangeSlide();
  },
}
</script>
