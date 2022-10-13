<template>
  <section class="bg-dark py-5" id="team">
    <div class="container">
      
      <!-- <div class="team-box d-flex gap-3">
        <img
          src="/assets/Team/Rony.png"
          alt="Rony"
          width="200"
          height="200"
          class="shadow rounded-circle"
        />
        <div class="">
          <h2 class="fs-1 text-light mt-4">RONY ZARIFE</h2>
          <p class="fs-5 mt-4 text-lite">
            Rony has a keen eye for detail and is deliberate in integrating
            simple and effective solutions to encountered challenges. His
            evolution went from interior design and engineering to management.
            This background adds value to every project as he has both respect
            for the design to be achieved, and the right skills to lead teams
          </p>
        </div>
      </div> -->
      
      <div class="team-box d-flex gap-3 flex-column align-items-center">
        <img
          src="/assets/Team/Rony.png"
          alt="Rony"
          width="200"
          height="200"
          class="shadow rounded-circle"
        />
        <div class="">
          <h2 class="fs-1 text-light mt-4 text-center sans">Rony Zarife</h2>
          <p class="fs-5 mt-4 text-lite text-center">
            Rony has a keen eye for detail and is deliberate in integrating
            simple and effective solutions to encountered challenges. His
            evolution went from interior design and engineering to management.
            This background adds value to every project as he has both respect
            for the design to be achieved, and the right skills to lead teams.
          </p>
        </div>
      </div>
      <img src="/assets/Team/Organogram-01.svg" alt="Organogram" class="img-fluid">
    </div>
  </section>
</template>
<style scoped>

/*--------------------------------------------------------------
# Sections & Section Header
--------------------------------------------------------------*/
section {
  padding: 80px 0;
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

</style>