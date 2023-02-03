<script setup>
import ButtonComponent from './Button.vue';
</script>

<template>
  <section id="join_free" class="position-relative">
    <!-- button container  -->
    <div class="btn_wrapper">
      <ButtonComponent type="button" text="Yes, I'm In" />
    </div>
    <div class="heading_div" style="padding-top: 4rem">
      <h2>Join For Free - No Charge!</h2>
      <h3>The Best Part is that there’s</h3>
    </div>

    <!-- container  -->
    <div class="container" id="marketing">
      <!-- row  -->
      <div class="row">
        <!-- col  -->
        <div class="col-md-4 text-center">
          <img
            src="../assets/images/multi-level-marketing.png"
            alt="multi-level-marketing"
          />
          <h3 class="multi-level-marketing">MLM RECRUITING</h3>
          <div class="underline"></div>
          <img
            src="../assets/images/digital-marketing1.png"
            alt="digital-marketing1"
            class="mt-0 mt-md-2"
          />
          <h3>FACEBOOK ADS</h3>
        </div>
        <!-- col  -->
        <div class="col-md-4 text-center">
          <img
            src="../assets/images/pay-per-click.png"
            alt="pay-per-click"
          />
          <h3>SEO/PPC/Youtube</h3>
          <div class="underline big_no_underline"></div>
          <div
            class="d-flex justify-content-center align-items-center"
          >
            <div class="underline_upper"></div>
            <h1 class="big_no flex-1">NO</h1>
            <div class="underline_upper"></div>
          </div>

          <div class="underline big_no_underline"></div>

          <img
            src="../assets/images/acceleration.png"
            alt="acceleration"
            style="margin-top: 1rem"
          />
          <h3>No Buying Inventory</h3>
        </div>
        <!-- col  -->
        <div class="col-md-4 text-center">
          <img src="../assets/images/bullhorn1.png" alt="bullhorn1" />
          <h3 class="affiliate">affiliate Marketing</h3>
          <div class="underline"></div>
          <img
            src="../assets/images/server.png"
            class="mt-md-2"
            alt="server"
          />
          <h3>Wordpress or Blogging</h3>
        </div>
      </div>
    </div>

    <!-- wrapper  -->
    <div class="wrapper">
      <div>
        <h2>The 6 day Accelerator</h2>
        <h3>IS Complimentary!</h3>
        <img src="../assets/images/Frame1.png" alt="Frame1" />
      </div>

      <div>
        <h2>In the 6-day</h2>
        <h3>Accelerator</h3>
        <p>
          you'll get the support of hundreds of other people just like
          you that are looking to build profitable passive income
          streams online! These people will help encourage you every
          step of your online business journey.
        </p>
        <img src="../assets/images/Frame2.png" alt="Frame2" />
      </div>
      <!-- button container  -->
      <div class="btn_container">
        <ButtonComponent type="button" text="Yes, I'm In" />
      </div>
      <h6>Join For Free - No Charge!</h6>

      <div>
        <h2>This is for</h2>
        <h3>you if you</h3>
        <p>
          Have already tried to build an online business before and
          <span>failed.</span>
        </p>
        <img src="../assets/images/Frame3.png" alt="Frame3" />
      </div>
      <div>
        <p>
          Are looking to transition away from a J-O-B and
          <span>replace</span> your primary income source
        </p>
        <img src="../assets/images/Frame4.png" alt="Frame4" />
      </div>
      <div>
        <h3 style="color: #0b9443">if you currently</h3>
        <h3 style="color: #0b9443">are interested</h3>
        <p>
          in starting a 6 figure online supplement
          <span>drop-shipping business</span> , automating it and
          working from the comfort of your own home part-time.
        </p>

        <img src="../assets/images/Frame5.png" alt="Frame5" />
      </div>
    </div>
    <!-- container  -->
    <div class="what_to_do container">
      <!-- row  -->
      <div class="row">
        <!-- col  -->
        <div class="col-md-1"></div>
        <!-- col  -->
        <div
          class="col-md-5 order-2 order-md-1 text-md-end text-center"
        >
          <img
            src="../assets/images/image_4.png"
            class="img-fluid"
            alt="image_4"
          />
        </div>
        <!-- col  -->
        <div class="order-1 col-md-6 order-md-2 pt-3">
          <h3 class="text-center text-md-start">If You</h3>

          <p class="text-center text-md-start">
            Want expert, credible sound <span>guidance</span> to
            filter all the other
            <span> "noisy marketers" </span>
            telling you what to do.
          </p>
        </div>
      </div>

      <div class="pt-5">
        <h3 class="text-center">If You</h3>
        <p class="text-center">
          Are ready to make real life-changing <span>progress</span>
        </p>
        <h3 class="text-center">in just 6-days!</h3>
        <img
          src="../assets/images/image_5.png"
          class="img-fluid d-block mx-auto"
          alt="image_5"
          style="height: 100%; width: 35rem"
        />
      </div>

      <div class="row ready_to_jump">
        <!-- col  -->
        <div class="col-md-1"></div>
        <!-- col  -->
        <div class="col-md-6 mb-0 mt-md-3 mt-0">
          <h3 class="text-center">Ready To Jump Into The</h3>
          <h3
            class="text-center"
            style="color: #43ac44; text-transform: uppercase"
          >
            NutraFunnels Accelerator?
          </h3>

          <!-- button container  -->
          <div class="btn_container">
            <ButtonComponent type="button" text="Yes, I'm In" />
          </div>
          <p class="text-center mb-0">Join For Free - No Charge!</p>
        </div>
        <div class="col-md-5">
          <img
            src="../assets/images/Untitled_11.png"
            class="img-fluid"
            alt="Untitled_11.png"
          />
        </div>
      </div>
    </div>
  </section>
</template>
