<template>
  <section class="content-inner">
    <div class="container">
      <div class="row align-items-center about-bx3">
        <div class="col-lg-6 m-b30">
          <div class="dz-media">
            <img
              src="@/assets/images/about/pic4.jpg"
              alt=""
              class="img1 aos-item aos-init aos-animate"
            />
          </div>
        </div>
        <div class="col-lg-6 m-b30 aos-item aos-init aos-animate">
          <div class="section-head style-1">
            <h6 class="sub-title text-primary">About Us</h6>
            <h2 class="title">We Provide You The Best Experience</h2>
          </div>
          <p>
            Integer pretium, nisi at aliquam faucibus, ligula leo sollicitudin ligula, RouterLink
            scelerisque magna nunc sit amet leo. Cras lobortis elementum orci, in lobortis velit
            gravida vel. In hac habitasse platea dictumst.
          </p>
          <div class="history-row m-b30">
            <div>
              <h2 class="year d-flex">
                <span class="counter"> <CountUp start-val="0" end-val="10" duration="15" /> </span>+
              </h2>
              <span class="text"
                >Years Of <br />
                Experience</span
              >
            </div>
            <div>
              <h2 class="awards d-flex">
                <span class="counter"><CountUp start-val="0" end-val="25" duration="15" /></span>+
              </h2>
              <span class="text"
                >Awards <br />
                Gained</span
              >
            </div>
            <div>
              <h2 class="sales d-flex">
                <span class="counter"><CountUp start-val="0" end-val="50" duration="15" /></span>+
              </h2>
              <span class="text"
                >Furniture <br />
                Sold</span
              >
            </div>
          </div>
          <RouterLink to="/about-us" class="btn shadow-primary btn-primary btn-rounded"
            >READ MORE <i class="m-l10 las la-plus"></i
          ></RouterLink>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import CountUp from 'vue-countup-v3'

export default defineComponent({
  components: { CountUp },
  setup() {
    return {}
  }
})
</script>

<style scoped></style>
