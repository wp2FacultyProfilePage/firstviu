<script src="./first.js"></script>
  <style scoped src="./first.css"></style>

    <template>
    <div>
      <head>
      <!-- Include Bootstrap CDN link -->
      <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
      />
      <!-- Include Font Awesome CDN link -->
      <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
      />
      <!-- You can add other head elements here -->
    </head>

   <div class="d-flex vh-100 justify-content-center align-items-center">
  <div class="p-2 flex-grow">
    <div class="smallContainer border shadow rounded">
      <div class="row g-0">
        <div class="col-sm-6 col-xs-12 d-none d-sm-block position-relative" id='leftCol'>
         <img :src="bldg" alt="Example Image" height="100%"/>
          <div id="pt-5 text-end w-100" class="position-absolute end-0 top-0">
            <a href="#" class="customBtn activeBtn">Log in</a><br />
            <a href="#" class="customBtn">Sign up</a>
          </div>
 
        </div>
        <div class="col-sm-6 col-xs-12">
          <div class="d-flex flex-column" style="height:100%">
 
            <div class="text-center d-sm-none d-xs-block">
              <div class="switch-button">
                <input class="switch-button-checkbox" type="checkbox"/>
                <label class="switch-button-label" for=""><span class="switch-button-label-span">Login</span></label>
              </div>
            </div>
 
            <div class="my-auto p-5">
              <div class="text-center">
                <div>
                  <img :src="imageUrl" alt="Example Image" height="200"/>
                </div>
                <h2 class="h3 pb-3">LOGIN</h2>
              </div>
              <form>
                <div class="position-relative my-3 inputGroup text-center">
                  <span class="position-absolute"><i class="far fa-user"></i></span>
                  <input type="email" class="border-0 border-bottom w-100" placeholder="Enter ID" />
                </div>
                <div class="position-relative my-3 inputGroup text-center">
                  <span class="position-absolute"><i class="far fa-eye-slash"></i></span>
                  <input type="password" class="border-0 border-bottom w-100" placeholder="Password" />
                </div>
                <div class="d-flex align-items-center justify-content-between pt-2 bg-white">
                  <a class="linkFlare" href="#"><small>Forgot Password?</small></a>
                  <button class="btn btn-accent px-4 rounded-pill">LOGIN</button>
                </div>
              </form>
            </div>
            <div>
              <div class="p-2 text-center" id="lsHeading">
                
              </div>
             
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
  </div>
    
  </template>
  
