< >
  <div class="faq-brand-area bg_cover" style="background-image: url(/assets/images/faq-bg.jpg);">
    <div class="container">
      <div class="row brand-active">
        <swiper :options="swiperOptions">
          <swiper-slide>
          <div class="brand-item">
            <a href="#"><img src="/assets/images/brand-2.png" alt="brand"></a>
          </div>
          </swiper-slide>
          <swiper-slide>
          <div class="brand-item">
            <a href="#"><img src="/assets/images/brand-2.png" alt="brand"></a>
          </div>
          </swiper-slide>
          <swiper-slide>
          <div class="brand-item">
            <a href="#"><img src="/assets/images/brand-2.png" alt="brand"></a>
          </div>
          </swiper-slide>
          <swiper-slide>
          <div class="brand-item">
            <a href="#"><img src="/assets/images/brand-2.png" alt="brand"></a>
          </div>
          </swiper-slide>
          <swiper-slide>
          <div class="brand-item">
            <a href="#"><img src="/assets/images/brand-2.png" alt="brand"></a>
          </div>
          </swiper-slide>
          <swiper-slide>
          <div class="brand-item">
            <a href="#"><img src="/assets/images/brand-2.png" alt="brand"></a>
          </div>
          </swiper-slide>
        </swiper>
      </div>
      <div class="row">
        <div class="col-lg-7">
          <div class="faq-items">
            <div class="faq-thumb">
              <img src="/assets/images/faq-thumb.jpg" alt="">
            </div>
            <div class="faq-content">
              <p>We are servicing a <br> global clients in <br> more than 100 <br> countries</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</ >


<script>
  import { Swiper, SwiperSlide, directive } from 'vue-awesome-swiper';
  import 'swiper/css/swiper.css';

  export default {
    name: "FaqBrandArea",
    components: {
      Swiper,
      SwiperSlide
    },
    directives: {
      swiper: directive
    },
    data() {
      return {
        swiperOptions: {
          slidesPerView : 5,
          loop: true,
          speed: 1000,
          spaceBetween : 30,
          autoplay: {
            delay: 3000,
            disableOnInteraction: false
          },
          // Responsive breakpoints
          breakpoints: {
            1024:{
              slidesPerView : 5
            },
            768:{
              slidesPerView : 4
            },
            640:{
              slidesPerView : 3
            },
            320:{
              slidesPerView : 2
            }
          }
        }
      }
    },
  }
</script>

<style scoped>

</style>
