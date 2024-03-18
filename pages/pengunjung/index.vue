<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
        <div class="my-3">
          <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
        </div>
        <div class="my-3 text-muted">menampilkan 1 dari 1</div>
        <table class="table">
          <thead>
            <tr>
              <td>#</td>
              <td>NAMA</td>
              <td>KATEGORI</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1.</td>
              <td>riqi</td>
              <td>Siswa</td>
              <td>26 Februari 2024, 12.52.00</td>
              <td>Baca</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <nuxt-link to="http://localhost:3000/">
      <button type="button" class="btn btn-secondary" disabled>KEMBALI</button>
    </nuxt-link>
  </div>
</template>