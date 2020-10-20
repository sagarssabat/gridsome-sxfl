<template>
  <Layout>
    <section class="sx-component sx-static-info sx-contact">
      <div class="sx-head">
        <h1 class="sx-head--page-title"><span>contact us</span></h1>
      </div>
      <div class="container">
        <div class="sx-body">
          <div class="section-content text-center">
            <p class="section__text">
              Your concern is our priority and we are happy to help you.
            </p>
            <div class="row mt-5">
              <div class="col-lg-6">
                <div class="contact__text text-left static-info">
                  <h3 class="content-title">REGISTERED USER</h3>
                  <p>
                    Please use the Support section of the app to contact us.
                  </p>
                  <h3 class="content-title">NOT A REGISTERED USER</h3>
                  <p>
                    Please fill in the details and we will take it from there
                  </p>
                  <p>
                    For additional queries, please contact us at
                    <a href="mailto:support@sportzxchange.com"
                      >support@sportzxchange.com</a
                    >
                  </p>
                  <!-- <address class="contact__address pt-2"> #345, 1st Floor,<br> 29th B Main Rd,<br> 1st Sector,<br> HSR
                      Layout,<br> Bengaluru, Karnataka 560102 </address> -->
                </div>
              </div>
              <div class="col-lg-6">
                <form class="contactus" id="contactForm">
                  <div class="form-group">
                    <input
                      type="text"
                      placeholder="Name"
                      class="form-control"
                      id="userName"
                      onkeypress="return isTextKey(event,this)"
                    />
                    <div class="errordiv"></div>
                  </div>
                  <div class="form-group">
                    <input
                      type="email"
                      placeholder="Email"
                      class="form-control"
                      id="userEmail"
                      onkeypress="return ValidateEmail(this)"
                    />
                    <div class="errordiv"></div>
                  </div>
                  <div class="form-group">
                    <input
                      type="tel"
                      placeholder="Number"
                      maxlength="12"
                      class="form-control"
                      id="userNumber"
                      onkeypress="return isNumberKey(event)"
                    />
                    <div class="errordiv"></div>
                  </div>
                  <div class="form-group">
                    <select id="userTopic" class="custom-select"></select>
                    <div class="errordiv"></div>
                  </div>
                  <div class="form-group">
                    <textarea
                      cols="30"
                      rows="5"
                      placeholder="Message"
                      class="form-control"
                      id="userMessage"
                    ></textarea>
                    <div class="errordiv"></div>
                  </div>
                  <div class="form-group text-center">
                    <div
                      class="g-recaptcha"
                      data-sitekey="6LfoXNgZAAAAAHTh6n3M-JEwvPquHNaDfLo6uUKj"
                    ></div>
                  </div>
                  <button
                    type="button"
                    class="sx-btn sx-btn-primary"
                    id="submit"
                  >
                    submit
                  </button>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Contact us",
  },
};
</script>

<style>
</style>