<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
      <view class="container-header">
        <image
          class="img"
          :style="{ width:150,height:150 }"
          :source="require('./../../assets/konjungtivitis.png')"
        />
      </view>
      <text class="judul">DIAGNOSA DAN INTERVENSI KEPERAWATAN</text>
      <text
        class="paragraph"
      >a. Nyeri ( akut atau kronis ) berhubungan dengan peradangan pada konjungtiva.</text>
      <text class="paragraph">Tujuan : Nyeri pasien berkurang atau hilang</text>
      <text class="paragraph">Intervensi :</text>
      <text class="paragraph list">1) Kaji tingkat nyeri klien</text>
      <text
        class="paragraph list"
      >2) Menjelaskan sebab dan akibat nyeri pada klien serta keluarganya</text>
      <text
        class="paragraph list"
      >3) Observasi adanya tanda-tanda ketidaknyamanan non verbal misalnya : eksprsi wajah, posisi tubuh gelisah, meringis</text>
      <text class="paragraph list">4) Anjurkan untuk beristirahat dalam ruangan yang tenang</text>
      <text class="paragraph list">5) Berikan kompres dingin jika memungkinkan</text>
      <text
        class="paragraph"
      >b. Gangguan sensori perseptual penglihatan berhubungan dengan kemunduran visus dan penurunan ketajaman penglihatan serta adanya proses peradangan, adanya sekret atau purulen pada kornea</text>
      <text class="paragraph">Tujuan : Sensori perseptual penglihatan kembali adekuat</text>
      <text class="paragraph">Intervensi :</text>
      <text class="paragraph list">1) Tentukan ketajaman penglihatan</text>
      <text
        class="paragraph list"
      >2) Observasi tanda-tanda dan gejala-gejala lebih lanjut (disorientasi)</text>
      <text class="paragraph list">3) Perhatikan pada suram atau penglihatan kabur dan iritasi</text>
      <text
        class="paragraph list"
      >4) Anjurkan pasien untuk menggunakan kaca mata untuk membatu mengurangi silau pada mata</text>
      <text class="paragraph list">5) Kolaborasi dengan dokter dalam pilihan intervensi medis</text>
      <text
        class="paragraph"
      >c. Intoleransi aktivitas berhubungan dengan kemunduran visus dan penurunan ketajaman penglihatan</text>
      <text class="paragraph">Tujuan : Klien dapat beraktivitas secara adekuat</text>
      <text class="paragraph">Intervensi :</text>
      <text class="paragraph list">1) Tentukan tingkat ansietas sekarang atau keadaan fisik</text>
      <text
        class="paragraph list"
      >2) Anjurkan klien untuk melakukan perawatan diri sesuai dengan kemampuan maksimal</text>
      <text
        class="paragraph list"
      >3) Menganjurkan klien mengatur periode istirahat konsisten di antara aktivitas</text>
      <text class="paragraph list">4) Anjurkan klien meningkatkan manajemen stres, teknik relaksasi</text>
      <text
        class="paragraph"
      >d. Resiko tinggi cidera atau trauma berhubungan dengan penurunan ketajaman penglihatan</text>
      <text class="paragraph">Tujuan : Tidak terjadi cedera atau trauma</text>
      <text class="paragraph">Intervensi :</text>
      <text class="paragraph list">1) Batasi aktivitas yang berlebihan</text>
      <text class="paragraph list">2) Pertahankan keamanan lingkungan</text>
      <text class="paragraph list">3) Berikan posisi nyaman pada pasien</text>
      <text class="paragraph list">4) Anjurkan klien untuk memodifikasi lingkungan</text>
    </scroll-view>
  </view>
</template>



<style>
.paragraph {
  font-size: 16;
  padding-left: 20;
  padding-right: 20;
  text-align: justify;
  padding-top: 5;
}
.list {
  padding-left: 30;
}
.judul {
  font-size: 20;
  padding-left: 20;
  padding-bottom: 22;
  font-weight: bold;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>