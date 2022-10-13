<template>
  <section class="position-relative hero" id="hero">
    <img src="/hero2.webp" alt="hero" class="img-fluid" id="hero-img" />

    <div class="hero-body text-light p-5 bg-glass" id="hero-body">
      <h1 class="h1 my-3 sans">
        Welcome to <br />
        EVERO Construction
      </h1>
      <nav
        class="d-flex justify-content-start align-items-start flex-column gap-3"
      >
        <a href="#about" class="hvr-black">ABOUT US</a>
        <a href="#team" class="hvr-black">OUR TEAM</a>
        <a href="#services" class="hvr-black">OUR SERVICES</a>
        <a href="#projects" class="hvr-black">OUR PROJECTS</a>
        <a href="#contact" class="hvr-black">CONTACT US</a>
      </nav>

      <a href="#contact" class="w-100 btn btn-outline-light mt-3">Get Started</a>
      <!-- <social-media class="w-50"></social-media> -->
    </div>
  </section>
</template>
<style>
.hero {
  margin-top: 150px;
  position: relative;
}
.hero-body {
  width: 35%;
  height: var(--hero-body-size);
  position: fixed;
  top: 0;
  top: var(--header-size);
  /* left: 50%; */
  right: 0;
  z-index: 2;
  transition: 0.5s;
}
a {
  width: 200px;
}
</style>