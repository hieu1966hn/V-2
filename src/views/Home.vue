<template>
  <article class="text-start">
    <header>
      <h1 class="fw-bold">Thông tin khu cách ly</h1>
    </header>
    <hr />
    <p>Tổng số phòng: 20</p>
    <p>Tổng số người cách ly: 88</p>
    <canvas id="myChart" width="400" height="400"></canvas>

  </article>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
