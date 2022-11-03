<template>
  <section class="container" id="projects">
    <div class="section-header">
      <h2 class="sans fs-2">Our Projects</h2>
      <!-- <p>
        Voluptatem quibusdam ut ullam perferendis repellat non ut consequuntur
        est eveniet deleniti
      </p> -->
    </div>

    <!-- Nav bar -->
    <nav class="d-flex gap-3 mx-auto fs-5 text-uppercase point flex-wrap justify-content-center">
      <!-- <a class="" @click="setTag('ALL')">All</a> -->
      <a class="" @click="setTag('Offices')">Offices</a>
      <a class="" @click="setTag('Residential')">Residential</a>
      <a class="" @click="setTag('HORECA')">HORECA</a>
      <a class="" @click="setTag('Exhibition')">Exhibition</a>
    </nav>

    <section class="d-flex gap-3 flex-wrap justify-content-center px-2">
      <project-card
        v-for="p in tabing"
        :key="p"
        :img="p.images[0]"
        :title="p.title"
        :project="p"
        class="shadow"
      ></project-card>
    </section>
  </section>
</template>
<script>
export default {
  data() {
    return {
      tag: "ALL",
      projects: [
        {
          tag: "Offices",
          title: "Ocean 360",
          baseURL: "",
          images: [
            `/Projects/Ocean360/O360-2-3.jpg`,
            `/Projects/Ocean360/O360-2-6.jpg`,
            `/Projects/Ocean360/O360-.jpg`,
            `/Projects/Ocean360/O360-0019.jpg`,
            `/Projects/Ocean360/O360-9904.jpg`,
            `/Projects/Ocean360/O360-9970.jpg`,
          ],
        },
        {
          tag: "Offices",
          title: "Opus",
          baseURL: "",
          images: [
            `/Projects/Opus/IMG_6233.jpg`,
            `/Projects/Opus/IMG_6248.jpg`,
            `/Projects/Opus/IMG_6254.jpg`,
            `/Projects/Opus/IMG_6350.jpg`,
            `/Projects/Opus/IMG_6400.jpg`,
            `/Projects/Opus/IMG_6409.jpg`,
          ],
        },
        {
          tag: "Offices",
          title: "Swiss Yachts",
          baseURL: "",
          images: [
            `/Projects/SwissYachts/IMG_6127.jpg`,
            `/Projects/SwissYachts/IMG_6132.jpg`,
            `/Projects/SwissYachts/IMG_6133.jpg`,
            `/Projects/SwissYachts/IMG_6149.jpg`,
            `/Projects/SwissYachts/IMG_6152.jpg`,
            `/Projects/SwissYachts/IMG_6182.jpg`,
          ],
        },
        {
          tag: "Residential",
          title: "Al Barari",
          baseURL: "",
          images: [
            `/Projects/Al_Barari/Iliana - high res 10.jpg`,
            `/Projects/Al_Barari/Iliana - high res 15.jpg`,
            `/Projects/Al_Barari/Iliana - high res 28.jpg`,
            `/Projects/Al_Barari/Iliana - high res 37.jpg`,
            `/Projects/Al_Barari/Iliana - high res 38.jpg`,
            `/Projects/Al_Barari/Iliana - high res 42.jpg`,
          ],
        },
        {
          tag: "Residential",
          title: "The Nest",
          baseURL: "",
          images: [
            `/Projects/The_Nest/1.jpg`,
            `/Projects/The_Nest/2.jpg`,
            `/Projects/The_Nest/3.jpg`,
            `/Projects/The_Nest/4.jpg`,
            `/Projects/The_Nest/5.jpg`,
            `/Projects/The_Nest/6.jpg`,
          ],
        },
        {
          tag: "Residential",
          title: "Al Zahia Villa",
          baseURL: "",
          images: [
            `/Projects/Al_Zahia_Villa/CHEZ3830-HDR-Edit.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3902-HDR-Edit.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3923-HDR.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3969-HDR.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3982-HDR.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ4115-HDR.jpg`,
          ],
        },
        {
          tag: "HORECA",
          title: "Prostylez",
          baseURL: "",
          images: [
            `/Projects/Prostylzes/CHEZ2721.jpg`,
            `/Projects/Prostylzes/CHEZ2736.jpg`,
            `/Projects/Prostylzes/CHEZ2763.jpg`,
            `/Projects/Prostylzes/CHEZ2805.jpg`,
            `/Projects/Prostylzes/CHEZ2875.jpg`,
            `/Projects/Prostylzes/CHEZ2889.jpg`,
          ],
        },
        {
          tag: "HORECA",
          title: "Clarity Cafe",
          baseURL: "",
          images: [
            `/Projects/ClarityCafe/1.jpg`,
            `/Projects/ClarityCafe/2.jpg`,
            `/Projects/ClarityCafe/3.jpg`,
            `/Projects/ClarityCafe/4.jpg`,
            `/Projects/ClarityCafe/5.jpg`,
            `/Projects/ClarityCafe/6.jpg`,
          ],
        },
        {
          tag: "HORECA",
          title: "Restaurant in Kuwait Pavilion",
          baseURL: "",
          images: [
            `/Projects/Restaurant_in_Kuwait_Pavilion/1.jpg`,
            `/Projects/Restaurant_in_Kuwait_Pavilion/2.jpg`,
            `/Projects/Restaurant_in_Kuwait_Pavilion/3.jpg`,
            `/Projects/Restaurant_in_Kuwait_Pavilion/4.jpg`,
            `/Projects/Restaurant_in_Kuwait_Pavilion/5.jpg`,
            `/Projects/Restaurant_in_Kuwait_Pavilion/6.jpg`,
          ],
        },
        {
          tag: "Exhibition",
          title: "EXPO 2020 GCC",
          baseURL: "",
          images: [
            `/Projects/EXPO_2020_GCC/1.jpg`,
            `/Projects/EXPO_2020_GCC/2.jpg`,
            `/Projects/EXPO_2020_GCC/3.jpg`,
            `/Projects/EXPO_2020_GCC/4.jpg`,
            `/Projects/EXPO_2020_GCC/5.jpg`,
            `/Projects/EXPO_2020_GCC/6.jpg`,
          ],
        },
        {
          tag: "Exhibition",
          title: "EXPO 2020 Kuwait",
          baseURL: "",
          images: [
            `/Projects/EXPO_2020_Kuwait/1.jpg`,
            `/Projects/EXPO_2020_Kuwait/2.jpg`,
            `/Projects/EXPO_2020_Kuwait/3.jpg`,
            `/Projects/EXPO_2020_Kuwait/4.jpg`,
            `/Projects/EXPO_2020_Kuwait/5.jpg`,
          ],
        },
      ],
    };
  },
  methods: {
    setTag(t) {
      this.tag = t;
    },
    visit(web) {
      location.href = `/${web}`;
    },
  },
  computed: {
    tabing() {
      if (this.tag == "ALL") return this.projects;
      return this.projects.filter((p) => p.tag == this.tag);
    },
  },
  mounted() {},
};
</script>

<style scoped>
a {
  width: fit-content;
}
nav {
  width: fit-content;
}
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
  padding-bottom: 30px;
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