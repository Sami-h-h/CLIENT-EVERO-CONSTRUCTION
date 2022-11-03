<template>
  <section id="contact" class="get-started section-bg">
    <div class="container">
      <div class="row justify-content-between gy-4">
        <div class="col-lg-5 d-flex align-items-center" data-aos="fade-up">
          <div class="w-100 h-100 content d-flex justify-content-center align-items-center gap-2 flex-wrap">
            
            <logo w="200"></logo>
            
            <div class="bg-light shadow-sm w-100 p-3">
              <strong class="sans">Email : </strong>
              <a href="mailto:info@evero.ae">info@evero.ae</a>
            </div>
            <div class="bg-light shadow-sm w-100 p-3">
              <strong class="sans">Number : </strong>
              <a href="tel:+971042611022">+971 (0) 426 11 0 22</a>
            </div>
            <div class="bg-light shadow-sm w-100 p-3">
              <strong class="sans">Address : </strong>
              <span
              >Office 301, Palazzo Venezia Bldg, Majan, Dubailand
              District, Dubai, United Arab Emirates
            </span>
            </div>


            <!-- <h3 class="sans fs-1">Contact Us</h3>

            <strong>Email : </strong
            ><a href="mailto:info@evero.ae">info@evero.ae</a>
            <br><br>

            <strong>Number : </strong
            ><a href="tel:+971042611022">+971 (0) 426 11 0 22</a>
            <br /><br>

            <strong>Address : </strong
            ><span
              >Main Office: Office 301, Palazzo Venezia Bldg, Majan, Dubailand
              District, Dubai, United Arab Emirates
            </span> -->
          </div>
        </div>

        <div class="col-lg-5" data-aos="fade">
          <Form></Form>
          <!-- <form
            action="forms/quote.php"
            method="post"
            class="php-email-form shadow-sm"
          >
            <h3>Get a quote</h3>
           
            <div class="row gy-3">
              <div class="col-md-12">
                <input
                  type="text"
                  name="name"
                  class="form-control"
                  placeholder="Name"
                  required
                />
              </div>

              <div class="col-md-12">
                <input
                  type="email"
                  class="form-control"
                  name="email"
                  placeholder="Email"
                  required
                />
              </div>

              <div class="col-md-12">
                <input
                  type="text"
                  class="form-control"
                  name="phone"
                  placeholder="Phone"
                  required
                />
              </div>

              <div class="col-md-12">
                <textarea
                  class="form-control"
                  name="message"
                  rows="6"
                  placeholder="Message"
                  required
                ></textarea>
              </div>

              <div class="col-md-12 text-center">
                <div class="loading">Loading</div>
                <div class="error-message"></div>
                <div class="sent-message">
                  Your quote request has been sent successfully. Thank you!
                </div>

                <button type="submit">Get a quote</button>
              </div>
            </div>
          </form> -->
        </div>
        <!-- End Quote Form -->
      </div>
    </div>
  </section>
</template>
<style scoped>
/*--------------------------------------------------------------
# Sections & Section Header
--------------------------------------------------------------*/
section {
  padding: 40px 0;
  overflow: hidden;
}

.section-bg {
  background-color: #f5f6f7;
}

.section-header {
  text-align: center;
  padding-bottom: 70px;
}

.section-header h2 {
  font-size: 32px;
  font-weight: 700;
  position: relative;
  color: #2e3135;
}

.section-header h2:before,
.section-header h2:after {
  content: "";
  width: 50px;
  height: 2px;
  background: var(--color-primary);
  display: inline-block;
}

.section-header h2:before {
  margin: 0 15px 10px 0;
}

.section-header h2:after {
  margin: 0 0 10px 15px;
}

.section-header p {
  margin: 0 auto 0 auto;
}

@media (min-width: 1199px) {
  .section-header p {
    max-width: 60%;
  }
}

/*--------------------------------------------------------------
# Get Started Section
--------------------------------------------------------------*/
.get-started .content {
  padding: 30px 0;
}

.get-started .content h3 {
  font-size: 36px;
  /* color: var(--); */
  font-weight: 600;
  margin-bottom: 25px;
  padding-bottom: 25px;
  position: relative;
}

.get-started .content h3:after {
  /* content: "";
  position: absolute;
  display: block;
  width: 200px;
  height: 4px;
  background: var(--color-primary);
  left: 0;
  bottom: 0; */
}

.get-started .content p {
  font-size: 14px;
}

.get-started .php-email-form {
  background: #fff;
  padding: 30px;
  height: 100%;
}

@media (max-width: 575px) {
  .get-started .php-email-form {
    padding: 20px;
  }
}

.get-started .php-email-form h3 {
  font-size: 14px;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.get-started .php-email-form p {
  font-size: 14px;
  margin-bottom: 20px;
}

.get-started .php-email-form .error-message {
  display: none;
  color: #fff;
  background: #df1529;
  text-align: left;
  padding: 15px;
  margin-bottom: 24px;
  font-weight: 600;
}

.get-started .php-email-form .sent-message {
  display: none;
  color: #fff;
  background: #059652;
  text-align: center;
  padding: 15px;
  margin-bottom: 24px;
  font-weight: 600;
}

.get-started .php-email-form .loading {
  display: none;
  background: #fff;
  text-align: center;
  padding: 15px;
  margin-bottom: 24px;
}

.get-started .php-email-form .loading:before {
  content: "";
  display: inline-block;
  border-radius: 50%;
  width: 24px;
  height: 24px;
  margin: 0 10px -6px 0;
  border: 3px solid #059652;
  border-top-color: #fff;
  -webkit-animation: animate-loading 1s linear infinite;
  animation: animate-loading 1s linear infinite;
}

.get-started .php-email-form input,
.get-started .php-email-form textarea {
  border-radius: 0;
  box-shadow: none;
  font-size: 14px;
  border-radius: 0;
}

.get-started .php-email-form input:focus,
.get-started .php-email-form textarea:focus {
  border-color: var(--color-primary);
}

.get-started .php-email-form input {
  padding: 12px 15px;
}

.get-started .php-email-form textarea {
  padding: 12px 15px;
}

.get-started .php-email-form button[type="submit"] {
  background: var(--color-primary);
  border: 0;
  padding: 10px 30px;
  color: #fff;
  transition: 0.4s;
  border-radius: 4px;
}

.get-started .php-email-form button[type="submit"]:hover {
  background: var(--dark-lite)
}

@-webkit-keyframes animate-loading {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

@keyframes animate-loading {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}
</style>