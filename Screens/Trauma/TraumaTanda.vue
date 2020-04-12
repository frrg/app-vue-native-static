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
      <text class="judul">TANDA DAN GEJALA</text>

      <text class="paragraph">1. Nyeri</text>
      <text class="paragraph">2. Enoftalmia (perpindahan mata yang abnormal ke belakang atau ke bawah)</text>
      <text class="paragraph">3. Hifema (darah didalam bilik depan mata)</text>
      <text class="paragraph">4. Adanya laserasi perdarahan, perubahan struktur konjugtiva, warna, dan memar.</text>
      <text class="paragraph">5. Robek,edema pada kornea.</text>
      <text class="paragraph">6. Pupul tidak beraksi terhadap cahaya, struktur pupil robek.</text>
    </scroll-view>
  </view>
</template>



<style>
.thumb {
  align-items: center;
  padding-top: 20;
}
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
  text-align:justify;
  padding-top: 5;
}
.list {
  padding-left: 30;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>