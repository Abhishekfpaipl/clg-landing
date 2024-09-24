<template>
  <div>
    <div class="d-md-block d-none">
      <img src="/img/desktop.jpg" class="w-100 min-vh-100 position-relative" alt="Banner">
      <div class="position-absolute d-flex justify-content-between align-items-center w-100 px-5" style="bottom: 10%;">
        <a href="https://web.clgoilindia.com" class="text-capitalize btn text-white fs-4"
          style="background-color: #FFA907;">click here to know about us</a>
        <a href="https://www.ariseol.com" class="text-capitalize btn text-white fs-4"
          style="background-color: #DB1D27;">click here to know
          about ARISEOL</a>
      </div>
    </div>
    <div class="d-md-none d-flex flex-column justify-content-between align-items-center w-100"
      style="background-color: black; height: 100vh;">

      <!-- Top Section -->
      <div class="px-2 w-100" style="position: fixed; top: 0; z-index: 1;">
        <img src="/img/clg.png" class="w-100 py-1" alt="clg logo">
        <p class="text-warning fs-4 my-2">India's leading manufacturer of lubrication & grease</p>
        <a href="https://web.clgoilindia.com" class="text-capitalize btn fs-4 rounded mb-5 mt-3"
          style="background-color: #FFA907;">click here to know about us</a>
      </div>

      <!-- Middle Section (acts as background) -->
      <div style="flex-grow: 1; background-color: black;">
        <!-- This section takes up the remaining space -->
      </div>

      <!-- Bottom Section -->
      <div class="w-100" style="position: fixed; bottom: 0; z-index: 1;">
        <img src="/img/mobile.jpg" class="w-100" alt="Banner">
        <a href="https://www.ariseol.com" class="w-100 text-capitalize btn text-white fs-3 rounded-0"
          style="background-color: #DB1D27;">click here to know ARISEOL</a>
      </div>
    </div>


  </div>
</template>

<script>
export default {
  data() {
    return {
    };
  }
};
</script>

<style scoped>
.card {
  position: relative;
  overflow: hidden;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(255, 0, 0, 0.5);
  /* opacity: 1; */
}

.card-title,
.card-text {
  position: relative;
  /* Make sure text is above the overlay */
  z-index: 1;
}

.card:hover .card-img {
  transform: scale(1.05);
}
</style>
