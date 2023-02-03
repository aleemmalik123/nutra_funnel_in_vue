<script setup>
import ButtonComponent from '../components/Button.vue';
import { defineEmits } from 'vue';

const { isModalOpen } = defineProps(['isModalOpen']);

const emit = defineEmits(['closeModal']);

const onClick = () => {
  emit('closeModal', false);
};
</script>

<template>
  <div
    class="modal fade show"
    :class="isModalOpen && 'show'"
    id="registerModal"
    tabindex="-1"
    aria-labelledby="registerModal"
    aria-hidden="true"
    :style="{ display: isModalOpen ? 'block' : 'none' }"
  >
    <div class="modal-dialog modal-lg">
      <div class="modal-content position-relative">
        <div class="modal-body">
          <div class="container-fluid">
            <div class="row">
              <div class="col-lg-8 col-md-10 mx-auto">
                <div class="form_container">
                  <form>
                    <h2>Sign up</h2>
                    <div class="mb-3">
                      <input
                        type="text"
                        class="form-control"
                        id="name"
                        placeholder="Name"
                      />
                    </div>
                    <div class="mb-3">
                      <input
                        type="text"
                        class="form-control"
                        id="email"
                        placeholder="Email"
                      />
                    </div>
                    <div class="mb-3">
                      <input
                        type="text"
                        class="form-control"
                        id="password"
                        placeholder="Password"
                      />
                    </div>

                    <div class="mb-3">
                      <input
                        type="text"
                        class="form-control"
                        id="phone"
                        placeholder="+1(xx)-xxxx"
                      />
                    </div>

                    <h4>Join for free-No charge!</h4>
                    <ButtonComponent
                      id="button"
                      type="button"
                      class="btn"
                      text="Join Us Now"
                      :handleClick="onClick"
                    />
                  </form>
                </div>
              </div>
            </div>
          </div>

          <img
            src="../assets/images/Group-222.png"
            alt="Group-222"
            class="left_img"
          />
          <img
            src="../assets/images/Group-55.png"
            alt="Group-55"
            class="right_img"
          />
        </div>
      </div>
    </div>
  </div>
</template>
