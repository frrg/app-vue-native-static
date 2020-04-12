<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
      <view class="container-header">
        <image
          class="img"
          :style="{ width:150,height:150 }"
          :source="require('./../../assets/trauma.png')"
        />
      </view>
      <text class="judul">DIAGNOSA KEPERAWATAN DAN INTERVENSI</text>
      <text
        class="paragraph"
      >1. Nyeri akut berhubungan dengan imflamasi pada kornea atau peningkatan tekanan intraokular dan kerusakan jaringan mata.</text>
      <text class="paragraph">Tujuan : nyeri berkurang, hilang atau terkontrol.</text>
      <text class="paragraph">Kriteria Hasil :</text>
      <text
        class="paragraph list"
      >a. Klien akan melaporkan penurunan nyeri progresif dan penghilangan nyeri setelah intervensi.</text>
      <text class="paragraph list">b. Klien tidak gelisah.</text>
      <text class="paragraph list">c. Klien mampu melakukan tindakan mengurangi nyeri.</text>
      <text class="paragraph">Intervensi dan Rasional :</text>
      <text
        class="paragraph list"
      >a. Kaji derajat nyeri setiap hari atau sesering mungkin jika diperlukan</text>
      <text
        class="paragraph list"
      >Rasional : nyeri trauma umumnya menjadi keluhan utama terutama nyeri akibat kerusakan kornea.</text>
      <text
        class="paragraph list"
      >b. Terangkan penyebab nyeri dan faktor/tindakan yang dapat memprovokasi nyeri.</text>
      <text
        class="paragraph list"
      >Rasional : nyeri disebabkan oleh efek kimiawi atau fisik benda dan nyeri dapat meningkat akibat provokasi: menekan mata terlalu kuat; gerakan mata tiba-tiba.</text>
      <text class="paragraph list">c. Lakukan kompres pada jaringan sekitar mata.</text>
      <text
        class="paragraph list"
      >Rasional : kompres dingin mungkin diperlukan pada trauma fisik akut dan jika kondisi stabil (agak lama), dapat digunakan teknik kompres hangat (jika tidak ada perdarahan).</text>
      <text class="paragraph list">d. Kolaborasi pemberian analgesik.</text>
      <text class="paragraph list">Rasional : analgesik berfungsi untuk menigkatkan ambang nyeri.</text>
      <text class="paragraph list">e. Ajarkan teknik distraksi dan relaksasi pada klien.</text>
      <text class="paragraph list">Rasional : mengurangi nyeri dengan manipulasi psikologis.</text>
    </scroll-view>
  </view>
</template>



<style>
.paragraph {
  font-size: 16;
  padding-left: 20;
  padding-right: 20;
  text-align:justify;
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