<template>
  <div class="w-100 bg-grey z-10" id="header">
    <div
      class="
        d-flex
        justify-content-between
        px-3
        align-items-center
        flex-row-reverse
      "
    >
      <!-- <menu-icon class="menu"></menu-icon> -->
      <i
        class="menu bi bi-app fs-1 pe-3"
        data-bs-toggle="offcanvas"
        data-bs-target="#offcanvasExample"
      ></i>
      <logo class="logo mx-auto" w="150"></logo>
    </div>

    <div
      class="offcanvas offcanvas-end w-75 text-light bg-glass"
      tabindex="-1"
      id="offcanvasExample"
      aria-labelledby="offcanvasExampleLabel"
    >
      <div class="offcanvas-header">
        <logo w="150" class="mx-auto" :white="true"></logo>
        <!-- <h5 class="offcanvas-title" id="offcanvasExampleLabel">Welcome to EVERO Construction</h5> -->
      </div>
      <div class="offcanvas-body d-flex justify-content-start align-items-center flex-column gap-2">
        
            <nav class="d-flex justify-content-start align-items-start flex-column gap-3">
                <a href="#about" class="hvr-black"><span data-bs-dismiss="offcanvas">ABOUT US</span></a>
                <a href="#team" class="hvr-black"><span data-bs-dismiss="offcanvas">OUR TEAM</span></a>
                <a href="#services" class="hvr-black"><span data-bs-dismiss="offcanvas">OUR SERVICES</span></a>
                <a href="#projects" class="hvr-black"> <span data-bs-dismiss="offcanvas">OUR PROJECTS</span></a>
                <a href="#contact" class="hvr-black"><span data-bs-dismiss="offcanvas">CONTACT US</span></a>
            </nav>
          <a href="#contact" class="w-100 btn btn-outline-light my-3"><span data-bs-dismiss="offcanvas" >Get Started</span></a>
            <!-- <social-media></social-media> -->
        <i class="mx-auto bi bi-arrow-right fs-3" data-bs-dismiss="offcanvas" ></i>
      </div>
    </div>
  </div>
</template>
<style>
.w-80{
    width: 80% !important;
}
.menu {
  display: none;
  /* position: absolute;
  left: 5rem;
  top: 3rem; */
  cursor: pointer;
  /* transform: scale(2); */
}
@media (max-width: 856px) {
  .hero-body {
    display: none;
  }
  .menu {
    display: block;
  }
  .logo {
    margin: 0 !important;
  }
}
</style>