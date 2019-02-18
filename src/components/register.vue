<template>
  <div>
    <!-- Start Register Form -->
    <section class="bg-light" id="register">
      <div class="container">
        <div class="row">
          <div class="col-5 box">
            <h5>Register</h5>
            <p class="login-text">Lorem ipsum dolor, sit amet consectetur  Ea aliquam, et quae ipsa. <br> Lorem, ipsum dolor sit amet consectetur adipisicing elit.
            <form>
                <div class="form-group">
                  <label class="form-style3">First Name</label>
                  <div class="form-box">
                    <input type="text" class="form-control">
                </div>
                </div>
                <div class="form-group">
                  <label class="form-style3">Last Name</label>
                  <div class="form-box">
                    <input type="text" class="form-control">
                  </div>
                </div>
                <div class="form-group">
                  <div class="row">
                    <div class="col-6 text-left">
                        <label class="form-style3">Email</label>
                        <div class="form-box">
                          <input type="text" class="form-control">
                        </div>
                    </div>
                    <div class="col-6">
                        <label class="form-style3">Phone number</label>
                        <div class="form-box">
                          <input type="text" class="form-control">
                        </div>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <label class="form-style3">Password</label>
                  <div class="form-box">
                    <input type="password" class="form-control">
                  </div>
                </div>
                <div class="form-group">
                  <div class="row">
                    <div class="col-6 text-left">
                        <label class="form-style3">Company name</label>
                        <div class="form-box">
                          <input type="text" class="form-control">
                        </div>
                    </div>
                    <div class="col-6">
                        <label class="form-style3">Position</label>
                        <div class="form-box">
                          <input type="text" class="form-control">
                        </div>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <div class="row">
                    <div class="col-6 text-left">
                        <label class="form-style3">Company NPWP</label>
                        <div class="form-box">
                          <input type="text" class="form-control">
                        </div>
                    </div>
                    <div class="col-6">
                        <label class="form-style3">Company Phone number</label>
                        <div class="form-box">
                          <input type="text" class="form-control">
                        </div>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <label class="form-style3">Address</label>
                  <div class="form-box">
                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                  </div>
                </div>
                <div class="form-group">
                  <label class="form-style3">Country</label>
                  <div class="form-box">
                      <select id="inputState" class="form-control">
                        <option selected>Choose...</option>
                        <option>...</option>
                      </select>
                  </div>
                </div>
                <div class="form-group">
                  <div class="row">
                    <div class="col-6 text-left">
                        <label class="form-style3">Province</label>
                        <div class="form-box">
                          <select id="inputState" class="form-control">
                            <option selected>Choose...</option>
                            <option>...</option>
                          </select>
                      </div>
                    </div>
                    <div class="col-6">
                        <label class="form-style3">City</label>
                        <div class="form-box">
                          <select id="inputState" class="form-control">
                            <option selected>Choose...</option>
                            <option>...</option>
                          </select>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <div class="row">
                    <div class="col-6 text-left">
                        <label class="form-style3">District</label>
                        <div class="form-box">
                            <select id="inputState" class="form-control">
                              <option selected>Choose...</option>
                              <option>...</option>
                            </select>
                        </div>
                    </div>
                    <div class="col-6">
                        <label class="form-style3">Zipcode</label>
                        <div class="form-box">
                          <select id="inputState" class="form-control">
                            <option selected>Choose...</option>
                            <option>...</option>
                          </select>
                      </div>
                    </div>
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
                  <small class="text-grey">if you have account, please <a class="text-second" href="#">login here</a></small>
                </div>
              </form>
          </div>
        </div>
      </div>
    </section>
    <!-- End Register Form -->
  </div>
</template>

<script>
export default {
  name: 'Register',
}
</script>
