<template>
  <div>
   <!-- Start Login Form -->
    <section class="bg-light" id="login">
      <div class="container">
        <div class="row">
          <div class="col-5 box">
            <h5>Login</h5>
            <p class="login-text">Lorem ipsum dolor, sit amet consectetur  Ea aliquam, et quae ipsa. <br> Lorem, ipsum dolor sit amet consectetur adipisicing elit.
            <form>
                <div class="form-group">
                  <label class="form-style3">Username or email</label>
                  <div class="form-box">
                    <input type="email" class="form-control">
                </div>
                </div>
                <div class="form-group">
                  <label class="form-style3">Password</label>
                  <div class="form-box">
                    <input type="password" class="form-control">
                  </div>
                </div>
                <div class="form-group form-check">
                  <div class="row">
                    <div class="col-6">
                      <input type="checkbox" class="form-check-input">
                      <label class="form-style3">Remember me</label>
                    </div>
                    <div class="col-6 text-right">
                        <a class="form-style2 text-main" href="#">Forget Password</a>
                    </div>
                  </div>
                </div>
                <div class="col text-center"> 
                    <button type="submit" class="btn btn-form">login</button>
                </div>
                <div class="hr-style1"></div>
                <div class="form-regis">
                  <small class="text-grey">if you doesn't have a account please <a class="text-second" href="#">register here</a></small>
                </div>
              </form>
          </div>
        </div>
      </div>
    </section>
    <!-- End Login Form -->
  </div>
</template>

<script>
export default {
  name: 'Login',
}
</script>
