<template>
  <div class="_form_2">
    <link
      href="https://fonts.googleapis.com/css2?family=Lato&amp;family=Montserrat&amp;family=Roboto&amp;family=IBM+Plex+Sans:wght@400;600&amp;display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      type="text/css"
      href="https://unpkg.com/intl-tel-input@17.0.18/build/css/intlTelInput.min.css"
    />

    <form
      method="POST"
      action="https://evero.activehosted.com/proc.php"
      id="_form_63470B83D5DAA_"
      class="_form _form_2 _inline-form _dark "
      novalidate=""
    >
      <input type="hidden" name="u" value="63470B83D5DAA" data-name="u" />
      <input type="hidden" name="f" value="2" data-name="f" />
      <input type="hidden" name="s" data-name="s" />
      <input type="hidden" name="c" value="0" data-name="c" />
      <input type="hidden" name="m" value="0" data-name="m" />
      <input type="hidden" name="act" value="sub" data-name="act" />
      <input type="hidden" name="v" value="2" data-name="v" />
      <input
        type="hidden"
        name="or"
        value="7aa6032b5f71d380a42788b524a3983f"
        data-name="or"
      />
      <div class="_form-content d-flex shadow p-2 justify-content-center align-items-center gap-3 flex-column">

        <h3 class=" fs-3 sans p-2">Get in touch !</h3>
        <div class="w-100 shadow-sm p-2 _form_element _x34659072 _full_width">
          <!-- <label for="firstname" class="_form-label">First Name*</label> -->
          <div class="_field-wrapper">
            <input
            class="single-line mt-2"
              type="text"
              id="firstname"
              name="firstname"
              placeholder="Type your first name"
              required=""
              data-name="firstname"
            />
          </div>
        </div>
        <div class="w-100 shadow-sm p-2 _form_element _x14030461 _full_width">
          <!-- <label for="lastname" class="_form-label">Last Name*</label> -->
          <div class="_field-wrapper">
            <input
            class="single-line mt-2"
              type="text"
              id="lastname"
              name="lastname"
              placeholder="Type your last name"
              required=""
              data-name="lastname"
            />
          </div>
        </div>
        <div class="w-100 shadow-sm p-2 _form_element _x29744549 _full_width">
          <!-- <label for="email" class="_form-label">Email*</label> -->
          <div class="_field-wrapper">
            <input
            class="single-line mt-2"
              type="text"
              id="email"
              name="email"
              placeholder="Type your email"
              required=""
              data-name="email"
            />
          </div>
        </div>
        <div class="w-100 shadow-sm p-2 _form_element _x18574581 _full_width">
          <!-- <label for="phone" class="_form-label">Phone*</label> -->
          <div class="_field-wrapper">
            <input
            class="single-line mt-2"
              type="text"
              id="phone"
              name="phone"
              placeholder="Type your phone number"
              required=""
              data-name="phone"
            />
          </div>
        </div>
        <div class="w-50 p-2 _button-wrapper _full_width">
          <button id="_form_2_submit" class="w-100 _submit btn btn-dark sans" type="submit">
            Submit
          </button>
        </div>
        <!-- <div class="_clear-element"></div> -->
      </div>
      <div class="_form-thank-you" style="display: none"></div>
    </form>
  </div>
</template>

<style >

.single-line{
  width: 100%;
  padding: .5rem;
  background-color: transparent !important;
  outline: none;
  border: none;
  /* border-bottom-style: solid;
  border-width: 1px; */
  /* border-color: var(--text-plus); */

}
/* 
#form_2 {
  font-size: 14px;
  line-height: 1.6;
  font-family: arial, helvetica, sans-serif;
  margin: 0;
}

#form_2 * {
  outline: 0;
}

._form_hide {
  display: none;
  visibility: hidden;
}

._form_show {
  display: block;
  visibility: visible;
}

#form_2._form-top {
  top: 0;
}

#form_2._form-bottom {
  bottom: 0;
}

#form_2._form-left {
  left: 0;
}

#form_2._form-right {
  right: 0;
}

#form_2 input[type="text"],
#form_2 input[type="tel"],
#form_2 input[type="date"],
#form_2 textarea {
  padding: 6px;
  height: auto;
  border: #979797 1px solid;
  border-radius: 4px;
  color: #000 !important;
  font-size: 14px;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

#form_2 textarea {
  resize: none;
}

#form_2 ._submit {
  -webkit-appearance: none;
  cursor: pointer;
  font-family: arial, sans-serif;
  font-size: 14px;
  text-align: center;
  background: #fff !important;
  border: 0 !important;
  -moz-border-radius: 3px !important;
  -webkit-border-radius: 3px !important;
  border-radius: 3px !important;
  color: #000 !important;
  padding: 10px !important;
}

#form_2 ._close-icon {
  cursor: pointer;
  background-image: url("https://d226aj4ao1t61q.cloudfront.net/esfkyjh1u_forms-close-dark.png");
  background-repeat: no-repeat;
  background-size: 14.2px 14.2px;
  position: absolute;
  display: block;
  top: 11px;
  right: 9px;
  overflow: hidden;
  width: 16.2px;
  height: 16.2px;
}

#form_2 ._close-icon:before {
  position: relative;
}

#form_2 ._form-body {
  margin-bottom: 30px;
}

#form_2 ._form-image-left {
  width: 150px;
  float: left;
}

#form_2 ._form-content-right {
  margin-left: 164px;
}

#form_2 ._form-branding {
  color: #fff;
  font-size: 10px;
  clear: both;
  text-align: left;
  margin-top: 30px;
  font-weight: 100;
}

#form_2 ._form-branding ._logo {
  display: block;
  width: 130px;
  height: 14px;
  margin-top: 6px;
  background-image: url("https://d226aj4ao1t61q.cloudfront.net/hh9ujqgv5_aclogo_li.png");
  background-size: 130px auto;
  background-repeat: no-repeat;
}

#form_2 .form-sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}

#form_2 .form-label,
#_form_2 ._form_element ._form-label {
  font-weight: bold;
  margin-bottom: 5px;
  display: block;
}

#form_2._dark ._form-branding {
  color: #333;
}

#form_2._dark ._form-branding ._logo {
  background-image: url("https://d226aj4ao1t61q.cloudfront.net/jftq2c8s_aclogo_dk.png");
}

#form_2 ._form_element {
  position: relative;
  margin-bottom: 10px;
  font-size: 0;
  max-width: 100%;
}

#form_2 ._form_element * {
  font-size: 14px;
}

#form_2 ._form_element._clear {
  clear: both;
  width: 100%;
  float: none;
}

#form_2 ._form_element._clear:after {
  clear: left;
}

#form_2 .form_element input[type="text"],
#_form_2 .form_element input[type="date"],
#_form_2 .form_element select,
#_form_2 ._form_element textarea:not(.g-recaptcha-response) {
  display: block;
  width: 100%;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  font-family: inherit;
}

#form_2 ._field-wrapper {
  position: relative;
}

#form_2 ._inline-style {
  float: left;
}

#form_2 ._inline-style input[type="text"] {
  width: 150px;
}

#form_2 ._inline-style:not(._clear) + ._inline-style:not(._clear) {
  margin-left: 20px;
}

#form_2 ._form_element img._form-image {
  max-width: 100%;
}

#form_2 ._form_element ._form-fieldset {
  border: 0;
  padding: 0.01em 0 0 0;
  margin: 0;
  min-width: 0;
}

#form_2 ._clear-element {
  clear: left;
}

#form_2 ._full_width {
  width: 100%;
}

#form_2 ._form_full_field {
  display: block;
  width: 100%;
  margin-bottom: 10px;
}

#form_2 input[type="text"].has_error,
#_form_2 textarea._has_error {
  border: #f37c7b 1px solid;
}

#form_2 input[type="checkbox"]._has_error {
  outline: #f37c7b 1px solid;
}

#form_2 ._error {
  display: block;
  position: absolute;
  font-size: 14px;
  z-index: 10000001;
}

#form_2 ._error._above {
  padding-bottom: 4px;
  bottom: 39px;
  right: 0;
}

#form_2 ._error._below {
  padding-top: 4px;
  top: 100%;
  right: 0;
}

#form_2 ._error._above ._error-arrow {
  bottom: 0;
  right: 15px;
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: 5px solid #f37c7b;
}

#form_2 ._error._below ._error-arrow {
  top: 0;
  right: 15px;
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-bottom: 5px solid #f37c7b;
}

#form_2 ._error-inner {
  padding: 8px 12px;
  background-color: #f37c7b;
  font-size: 14px;
  font-family: arial, sans-serif;
  color: #fff;
  text-align: center;
  text-decoration: none;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
}

#form_2 ._error-inner._form_error {
  margin-bottom: 5px;
  text-align: left;
}

#form_2 ._button-wrapper ._error-inner._form_error {
  position: static;
}

#form_2 ._error-inner._no_arrow {
  margin-bottom: 10px;
}

#form_2 ._error-arrow {
  position: absolute;
  width: 0;
  height: 0;
}

#form_2 ._error-html {
  margin-bottom: 10px;
}

.pika-single {
  z-index: 10000001 !important;
}

#form_2 input[type="text"].datetime_date {
  width: 69%;
  display: inline;
}

#form_2 select.datetime_time {
  width: 29%;
  display: inline;
  height: 32px;
}

#form_2 input[type="date"].datetime_date {
  width: 69%;
  display: inline-flex;
}

#form_2 input[type="time"].datetime_time {
  width: 29%;
  display: inline-flex;
}

@media all and (min-width: 320px) and (max-width: 667px) {
  ::-webkit-scrollbar {
    display: none;
  }

  #form_2 {
    margin: 0;
    width: 100%;
    min-width: 100%;
    max-width: 100%;
    box-sizing: border-box;
  }

  #form_2 * {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    font-size: 1em;
  }

  #form_2 ._form-content {
    margin: 0;
    width: 100%;
  }

  #form_2 ._form-inner {
    display: block;
    min-width: 100%;
  }

  #form_2 .form-title,
  #_form_2 ._inline-style {
    margin-top: 0;
    margin-right: 0;
    margin-left: 0;
  }

  #form_2 ._form-title {
    font-size: 1.2em;
  }

  #form_2 ._form_element {
    margin: 0 0 20px;
    padding: 0;
    width: 100%;
  }

  #form_2 .form-element,
  #_form_2 .inline-style,
  #_form_2 input[type="text"],
  #form_2 label,
  #form_2 p,
  #form_2 textarea:not(.g-recaptcha-response) {
    float: none;
    display: block;
    width: 100%;
  }

  #form_2 ._row._checkbox-radio label {
    display: inline;
  }

  #form_2 .row,
  #_form_2 p,
  #form_2 label {
    margin-bottom: 0.7em;
    width: 100%;
  }

  #form_2 .row input[type="checkbox"],
  #_form_2 ._row input[type="radio"] {
    margin: 0 !important;
    vertical-align: middle !important;
  }

  #form_2 ._row input[type="checkbox"] + span label {
    display: inline;
  }

  #form_2 ._row span label {
    margin: 0 !important;
    width: initial !important;
    vertical-align: middle !important;
  }

  #form_2 ._form-image {
    max-width: 100%;
    height: auto !important;
  }

  #form_2 input[type="text"] {
    padding-left: 10px;
    padding-right: 10px;
    font-size: 16px;
    line-height: 1.3em;
    -webkit-appearance: none;
  }

  #form_2 input[type="radio"],
  #form_2 input[type="checkbox"] {
    display: inline-block;
    width: 1.3em;
    height: 1.3em;
    font-size: 1em;
    margin: 0 0.3em 0 0;
    vertical-align: baseline;
  }

  #form_2 button[type="submit"] {
    padding: 20px;
    font-size: 1.5em;
  }

  #form_2 ._inline-style {
    margin: 20px 0 0 !important;
  }
}

#form_2 {
  position: relative;
  text-align: left;
  margin: 25px auto 0;
  padding: 20px;
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  *zoom: 1;
  background: #e5e5e5 !important;
  border: 0px solid #b0b0b0 !important;
  max-width: 500px;
  -moz-border-radius: 3px !important;
  -webkit-border-radius: 3px !important;
  border-radius: 3px !important;
  color: #000 !important;
}

#form_2 ._form-title {
  font-size: 22px;
  line-height: 22px;
  font-weight: 600;
  margin-bottom: 0;
}

#form_2:before,
#form_2:after {
  content: " ";
  display: table;
}

#form_2:after {
  clear: both;
}

#form_2._inline-style {
  width: auto;
  display: inline-block;
}

#form_2.inline-style input[type="text"],
#_form_2._inline-style input[type="date"] {
  padding: 10px 12px;
}

#form_2._inline-style button._inline-style {
  position: relative;
  top: 27px;
}

#form_2._inline-style p {
  margin: 0;
}

#form_2._inline-style ._button-wrapper {
  position: relative;
  margin: 27px 12.5px 0 20px;
}

#form_2 ._form-thank-you {
  position: relative;
  left: 0;
  right: 0;
  text-align: center;
  font-size: 18px;
}

@media all and (min-width: 320px) and (max-width: 667px) {
  #form_2._inline-form._inline-style ._inline-style._button-wrapper {
    margin-top: 20px !important;
    margin-left: 0 !important;
  }
}

#form_2 .iti.iti--allow-dropdown.iti--separate-dial-code {
  width: 100%;
}

#form_2 .iti input {
  width: 100%;
  height: 32px;
  border: #979797 1px solid;
  border-radius: 4px;
}

#form_2 .iti--separate-dial-code .iti__selected-flag {
  background-color: #fff;
  border-radius: 4px;
}

#form_2 .iti--separate-dial-code .iti__selected-flag:hover {
  background-color: rgba(0, 0, 0, 0.05);
}

#form_2 .iti__country-list {
  border-radius: 4px;
  margin-top: 4px;
  min-width: 460px;
}

#form_2 .iti__country-list--dropup {
  margin-bottom: 4px;
}

#form_2 .phone-error-hidden {
  display: none;
}

#form_2 .phone-error {
  color: #e40e49;
}

#form_2 .phone-input-error {
  border: 1px solid #e40e49 !important;
}

#form_2 ._form_1 {
  font-family: "MADE Evolve Sans";
  margin-top: 150px;
}

#form_2 ._submit {
  font-family: "MADE Evolve Sans";
} */
</style>