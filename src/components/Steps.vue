<script setup>
import StepComponent from './Step.vue';
</script>

<template>
  <section id="become_success">
    <h2>How to become successful</h2>
    <h3>in 5 steps</h3>
    <!-- container fluid  -->
    <div class="container-fluid">
      <!-- row  -->
      <div class="row">
        <!-- col  -->
        <div class="col-md-4 text-md-end text-center left_div">
          <div>
            <StepComponent
              text="Spy"
              desc=" First we use insider information to find outwhat supplement
                  funnels are hot."
            />
          </div>
          <div>
            <StepComponent
              text="Funnel hack"
              desc="First we use insider information to find out what
                supplement funnels are hot."
              className="text-md-end text-center"
            />
          </div>
        </div>
        <!-- col  -->
        <div class="col-md-4 middle_div">
          <div class="position-relative">
            <img src="../assets/images/Frame6.png" alt="Frame6" />
            <img
              class="global"
              src="../assets/images/global-outsourcing.png"
              alt="global-outsourcing"
            />
          </div>

          <div class="text-center">
            <StepComponent
              text="Outsource"
              desc="We find an offshore outsourcer to put the whole funnel
                together for us."
            />
          </div>
        </div>
        <!-- col  -->
        <div class="col-md-4 right_div">
          <div class="text-md-start text-center">
            <StepComponent
              text="Rinse & repeat"
              desc="Then we rinse and repeat! You can do this again and
                again and build as many NutraFunnels as you want! it's
                just that SIMPLE!"
            />
          </div>
          <div class="text-md-start text-center">
            <StepComponent
              text="Traffic outsource"
              desc="Then we outsource all of the traffic-running to an
                affiliate network and PROFIT!"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
