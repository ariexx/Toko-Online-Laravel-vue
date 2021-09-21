<template>
  <div class="col-lg-8">
    <h4 class="mb-4">
      Informasi Pembeli:
    </h4>
    <div class="user-checkout">
      <form>
        <div class="form-group">
          <label for="namaLengkap">Nama lengkap</label>
          <input type="text" class="form-control" id="namaLengkap" aria-describedby="namaHelp" placeholder="Masukan Nama" />
        </div>
        <div class="form-group">
          <label for="namaLengkap">Email Address</label>
          <input type="email" class="form-control" id="emailAddress" aria-describedby="emailHelp" placeholder="Masukan Email" />
        </div>
        <div class="form-group">
          <label for="namaLengkap">No. HP</label>
          <input type="text" class="form-control" id="noHP" aria-describedby="noHPHelp" placeholder="Masukan No. HP" />
        </div>
        <div class="form-group">
          <label for="alamatLengkap">Alamat Lengkap</label>
          <textarea class="form-control" id="alamatLengkap" rows="3"></textarea>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "DetailCustomer",
};
</script>

<style></style>
