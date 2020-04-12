<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
      <view class="container-header">
        <image
          class="img"
          :style="{ width:150,height:150 }"
          :source="require('./../../assets/butawarna.png')"
        />
      </view>
      <text class="judul">D. MANIFESTASI KLINIS</text>

      <text
        class="paragraph"
      >&nbsp;&nbsp;&nbsp;Tanda seorang mengalami buta warna tergandung pada beberapa faktor apakah kondisinya disebabkan faktor genetik, penyakit, dan tingkat buta warnanya sebagian atau total. Gejala umumnya adalah kesulitan membedakan warna merah dan hijau yang paling sering terjadi, atau kesulitan membedakan warna biru dan hijau jarang ditemukan.Gejala untuk kasus yang lebih serius berupa objek terlihat dalam bentuk bayangan abu-abu kondisi ini sangat jarang ditemukan dan penglihatan berkurang.</text>
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
  text-align: justify;
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