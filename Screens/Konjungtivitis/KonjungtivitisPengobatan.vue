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
      <text class="judul">PENGOBATAN</text>
      <text class="paragraph">1. Konjungtivitis virus biasanya tidak diobati, karena akan sembuh sendiri dalam beberapa hari.
        Walaupun demikian, beberapa dokter tetap akan memberikan larutan astringen agar mata
        senantiasa bersih. </text>
      <text class="paragraph">2. Obat tetes atau salep antibiotik</text>
      <text
        class="paragraph"
      >3. Tablet atau tetes mata antihistamin cocok diberikan pada konjungtivitis alergi.</text>
      <text
        class="paragraph"
      >4. Untuk konjungtivitis papiler raksasa, pengobatan utama adalah menghentikan paparan dengan benda yang diduga sebagai penyebab, misalnya berhenti menggunakan lensa kontak</text>
    </scroll-view>
  </view>
</template>



<style>
.judul {
  font-size: 20;
  padding-left: 20;
  padding-bottom: 22;
  font-weight: bold;
}
.paragraph {
  font-size: 16;
  padding-left: 20;
  padding-right: 20;
  text-align: justify;
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