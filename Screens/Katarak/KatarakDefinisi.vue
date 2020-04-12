<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/katarak.png')"
      />
    </view>
    <text class="judul">A. DEFINISI</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Katarak merupakan penyakit mata yang ditandai dengan mengeruhnya lensa mata,
      sehingga membuat penglihatan kabur. Kondisi ini umumnya terjadi pada lansia, dan bisa terjadi pada
      salah satu atau kedua mata sekaligus. Meski demikian, katarak bukan jenis penyakit menular.
    </text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;
      Lensa mata adalah bagian transparan di belakang pupil (titik hitam di tengah mata),
      yang berfungsi untuk memfokuskan cahaya yang masuk melalui mata ke retina agar objek
      dapat terlihat jelas. Seiring bertambahnya usia, protein pada lensa akan menggumpal dan
      perlahan-lahan membuat lensa keruh dan berkabut. Hal ini menyebabkan penglihatan
      menjadi kabur dan tidak jelas.
    </text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Katarak adalah penyebab utama kebutaan di Indonesia.
      Dari hasil survey kebutaan di 15 provinsi tahun 2014-2016, diketahui 70-80% penyebab utama kebutaan
      dan gangguan penglihatan di Indonesia adalah katarak.
    </text>
    </scroll-view>
  </view>
</template>



<style>
.judul {
  font-size: 20;
  padding-left:20;
  padding-bottom:22;
  font-weight: bold;
}
.paragraph {
  font-size: 16;
  padding-left: 20;
  padding-right: 20;
  text-align:justify;
  padding-top: 5;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>