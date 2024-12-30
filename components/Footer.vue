<template>
  <footer class="bg-dark text-white py-4">
    <div class="container">
      <div class="row">
        <!-- Alamat -->
        <div class="col-md-6 mb-3">
          <h5>Alamat</h5>
          <p>
            Jl Depok Kel. Sukamenak Kec. Purbaratubratu <br>
            Kota Tasikmalaya.<br>
            Kode Pos: 46196.
          </p>
          <p>
            <i class="bi bi-telephone-fill"></i> +62265312059
          </p>
          <p>
            <i class="bi bi-envelope-fill"></i> info@smkn4-tsm.sch.id
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer a:hover {
  text-decoration: underline;
}

.social-icons i {
  font-size: 1.5rem;
}
</style>
