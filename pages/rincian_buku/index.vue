<template>
  <div class="container p-2 mt-3">
    <div class="row mt-4">
      <div class="col-3">
        <img src="~/assets/img/cover 2.jpg" class="cover" alt="cover 1" width="270px">
      </div>
      <div class="col-4">
        <h2>Rincian Buku</h2>
        <p>Judul buku : hikayat majapahit</p>
        <p>Penulis :elex media </p>
        <p>Tahun terbit :20 januari 2020 </p>
        <p>Halaman : 200</p>
        <p>Kategori : Dongeng</p>
        <p>ISBN : 978 634 567 890</p>
      </div>
    </div>
    <div class="row">
      <p>.</p>
    </div>
    <nuxt-link to="/buku/">
      <button type="button" class="btn btn-secondary" disabled>KEMBALI</button>
    </nuxt-link>
  </div>
</template>