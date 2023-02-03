<script setup>
import { ref } from 'vue';
import ButtonComponent from './Button.vue';
import RegisterModal from '../modals/RegisterModal.vue';

const isModalOpen = ref(false);

const onClick = () => {
  isModalOpen.value = true;
};
</script>
<template>
  <header>
    <div class="header_bg_img">
      <!-- logo div  -->
      <div class="text-center">
        <img
          src="../assets/images/Logo_1.png"
          class="header_logo img-fluid"
          alt="logo"
        />
      </div>

      <!-- header content  -->
      <div class="header_content">
        <div class="container-fluid">
          <div class="row g-0">
            <!-- col-3  -->
            <div class="col-3">
              <div class="header_content_left">
                <img
                  class="img-fluid"
                  src="../assets/images/Group-2.png"
                  alt="ROC281"
                />
              </div>
            </div>
            <!-- col-6  -->
            <div class="col-6 position-relative">
              <div class="header_content_middle text-center">
                <div
                  class="position-relative"
                  style="display: inline-block"
                >
                  <h1 data-text="Join Our">Join Our</h1>
                </div>

                <p class="para1">
                  6-Day Health-Supplement Drop-Shipping Business
                  Accelerator
                </p>
                <p class="para2">
                  Discover how to build a 6 figure Supplement
                  Drop-shipping Business In 6 Days WITHOUT Paying for
                  Facebook Ads Or Traffic!
                </p>
              </div>

              <!-- register div  for larger screen >= 992px -->
              <div class="register m-0 text-center d-none d-lg-block">
                <h2>6 days</h2>
                <!-- img  -->
                <img
                  src="../assets/images/Group-22.png"
                  class="computer_img img-fluid"
                  alt="Group-22"
                />

                <div class="btn_div">
                  <ButtonComponent
                    type="button"
                    text="Register now"
                    :handleClick="onClick"
                  />
                </div>
              </div>
            </div>
            <!-- col-3  -->
            <div class="col-3">
              <div class="header_content_right">
                <img
                  class="img-fluid"
                  src="../assets/images/Group-5.png"
                  alt="ROC281_1(1)"
                />
              </div>
            </div>
            <!-- register div  -->
            <div class="register m-0 text-center d-lg-none">
              <h2>6 days</h2>
              <img
                src="../assets/images/Group-22.png"
                alt="Group-22"
              />
              <div class="btn_div">
                <ButtonComponent
                  type="button"
                  text="Register now"
                  :handleClick="onClick"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- modal open  -->
    <RegisterModal
      :isModalOpen="isModalOpen"
      @closeModal="
        (value) => {
          isModalOpen = value;
        }
      "
    />
  </header>
</template>
