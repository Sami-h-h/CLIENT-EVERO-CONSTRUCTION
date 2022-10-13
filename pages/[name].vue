<template>
  <main>
    <Head>
      <Title> {{ $route.params.name }} </Title>
    </Head>
    <pagination>
      <strong class="text-secondary"> {{ title }} </strong>
    </pagination>

    <!-- Swiper -->
    <div class="swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="p in project.images" :key="p">
          <div class="swiper-zoom-container">
            <img :src="p" :alt="title" class="img-fluid" width="500" />
          </div>
        </div>
      </div>
      <!-- Add Pagination -->
      <div class="swiper-pagination"></div>
    </div>
  </main>
</template>
<script>
export default {
  data() {
    return {
      title: this.$route.params.name,
      images: [],

      projects: [
        {
          tag: "Offices",
          title: "Ocean360",
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
          title: "SwissYachts",
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
          title: "Al_Barari",
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
          title: "The_Nest",
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
          title: "Al_Zahia_Villa",
          baseURL: "",
          images: [
            `/Projects/Al_Zahia_Villa/CHEZ3830-HDR-EDIT.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3902-HDR-EDIT.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3923-HDR.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3969-HDR.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ3982-HDR.jpg`,
            `/Projects/Al_Zahia_Villa/CHEZ4115-HDR.jpg`,
          ],
        },
        {
          tag: "HORECA",
          title: "Prostylzes",
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
          title: "Clarity_Café",
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
          title: "Restaurant_in_Kuwait_Pavilion",
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
          title: "EXPO_2020_GCC",
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
          title: "EXPO_2020_Kuwait",
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
  computed: {
    project() {
      return this.projects.filter((p) => p.title == this.$route.params.name)[0];
    },
  },
  mounted() {
    var swiper = new Swiper(".swiper", {
      pagination: {
        el: ".swiper-pagination",
        // type: "progressbar",
      },
      zoom: true,
      grabCursor: true,
      spaceBetween: 10,
    });
  },
  head() {
    return {
      link: [
        {
          rel: "stylesheet",
          href: "https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css",
        },
      ],
      script: [
        {
          src: "https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js",
        },
      ],
    };
  },
};
</script>
<style scoped>
.swiper {
  width: 50%;
  height: 500px;
}
@media (max-width: 900px) {
  .swiper {
    width: 90%;
    height: 90%;
  }
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;

  /* Center slide text vertically */
  display: -webkit-box;
  display: -ms-flexbox;
  display: -webkit-flex;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-justify-content: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  -webkit-align-items: center;
  align-items: center;
}

.swiper-pagination {
  /* position: static !important; */
  margin-top: 20px;
}
</style>