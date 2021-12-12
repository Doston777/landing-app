<template>
  <section id="pricing" class="section mt-5 mt-sm-5">
    <div class="container">
      <div class="text-center">

                    <span class="rounded-pill bg-white shadow bold py-2 px-4 py-sm-2 px-sm-4">
                        <i class="fas fa-lightbulb mr-2 mr-sm-2 text-primary"></i>

                        <span class="text-primary">
                            Save more
                        </span>

                        with these awesome plans
                    </span>
        
        <h1 class="mt-5 heading">
          Transparent pricing
        </h1><br>
        
        <p class="lead text-muted">
          Our plans have everything you need to take your app to the next level. No hidden fees.
        </p>
        
        <ul class="nav nav-pills mb-3 mb-sm-3 mt-5 mt-sm-5 justify-content-center" id="pills-tab"
            role="tablist">
          <li class="nav-item" role="presentation">
            <button class="nav-link active" id="pills-home-tab" data-bs-toggle="pill" data-bs-target="#pills-home"
               role="tab" aria-controls="pills-home" aria-selected="true" type="button">Monthly</button>
          </li>
          
          <li class="nav-item" role="presentation">
            <button class="nav-link" id="pills-profile-tab" data-bs-toggle="pill" data-bs-target="#pills-profile"
               role="tab" aria-controls="pills-profile" aria-selected="false" type="button">Yearly</button>
          </li>
        </ul>
        
        <div class="tab-content" id="pills-tabContent">
          <div class="tab-pane fade show active" id="pills-home" role="tabpanel"
               aria-labelledby="pills-home-tab">
            <div class="row">
              <div class="col-md-4 border-yellow">
                <div class="p-5 p-sm-5">
                  <div class="text-center">
                    <h4 class="mb-sm-3 mb-3 text-alternate text-capitalize bold">basic</h4>
                    
                    <p class="unique-margin">For individuals</p>
                    
                    <p class="display-3 price">$0/<i>mo</i></p>
                    
                    <a href="#" class="btn btn-light">I want this <i class="fa fa-arrow-right"
                                                                     aria-hidden="true"></i></a>
                  </div>
                </div>
              </div>
              
              <div class="col-md-4">
                <div class="p-5 p-sm-5">
                  <div class="text-center">
                    <h4 class="mb-sm-3 mb-3 text-danger text-capitalize bold">business</h4>
                    
                    <p>For small business</p>
                    
                    <p class="display-3 price">$49.9/<i>mo</i></p>
                    
                    <a href="#" class="btn btn-primary">I want this <i class="fa fa-arrow-right"
                                                                       aria-hidden="true"></i></a>
                  </div>
                </div>
              </div>
              
              <div class="col-md-4">
                <div class="p-5 p-sm-5">
                  <div class="text-center">
                    <h4 class="mb-sm-3 mb-3 text-alternate text-capitalize bold">enterprise</h4>
                    
                    <p>For large companies</p>
                    
                    <p class="display-3 price">$19.9/<i>mo</i></p>
                    
                    <a href="#" class="btn btn-light">I want this <i class="fa fa-arrow-right"
                                                                     aria-hidden="true"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
          <div class="tab-pane fade" id="pills-profile" role="tabpanel"
               aria-labelledby="pills-profile-tab">
            <div class="row">
              <div class="col-md-4">
                <div class="p-5">
                  <div class="text-center">
                    <h4 class="mb-sm-3 mb-3 text-alternate text-capitalize bold">basic</h4>
                    
                    <p class="unique-margin">For individuals</p>
                    
                    <p class="display-3 price">$0/<i>mo</i></p>
                    
                    <a href="#" class="btn btn-light">I want this <i class="fa fa-arrow-right"
                                                                     aria-hidden="true"></i></a>
                  </div>
                </div>
              </div>
              
              <div class="col-md-4">
                <div class="p-5">
                  <div class="text-center">
                    <h4 class="mb-sm-3 mb-3 text-danger text-capitalize bold">business</h4>
                    
                    <p>For small business</p>
                    
                    <p class="display-3 price">$39.9/<i>mo</i></p>
                    
                    <a href="#" class="btn btn-primary">I want this <i class="fa fa-arrow-right"
                                                                       aria-hidden="true"></i></a>
                  </div>
                </div>
              </div>
              
              <div class="col-md-4">
                <div class="p-5">
                  <div class="text-center">
                    <h4 class="mb-sm-3 mb-3 text-alternate text-capitalize bold">enterprise</h4>
                    
                    <p>For large companies</p>
                    
                    <p class="display-3 price">$14.9/<i>mo</i></p>
                    
                    <a href="#" class="btn btn-light">I want this <i class="fa fa-arrow-right"
                                                                     aria-hidden="true"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    
    
    </div>
  </section>
</template>

<script>
	export default {
		name: "Prising"
	}
</script>

<style scoped>

</style>