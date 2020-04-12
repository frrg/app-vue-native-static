<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/glaukoma.png')"
      />
    </view>
    <text class="judul">H. PENGOBATAN</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Saat ini belum ada terapi yang dapat mengobati glaukoma secara total. Terapi yang dilakukan hanya untuk mempertahankan fungsi penglihatan yang tersisa saat pemeriksaan dan meningkatkan kualitas hidup. Cara yang dilakukan adalah dengan menurunkan tekanan pada bola mata yang merupakan faktor risiko utama. Terapi yang dilakukan dengan obat-obatan, tindakan laser, dan tindakan bedah. Obat-obatan yang diberikan berfungsi untuk menurunkan produksi cairan bola mata atau untuk memperlancar aliran keluar cairan sehingga dapat menurunkan tekanan pada bola mata. (Pusdatin RI, 2019)
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