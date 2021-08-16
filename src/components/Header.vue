<template>
  <header class="d-flex bg-dark py-2 px-4" aria-label="Fifth navbar example">
    <form class="w-25">
      <input
        class="form-control"
        type="text"
        placeholder="Search"
        aria-label="Search"
      />
    </form>
    <router-link class="btn btn-success ms-auto" to="/addperson">
      Thêm người cách ly
    </router-link>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
