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
      <text class="judul">F. PENGOBATAN</text>
      <text
        class="paragraph"
      >&nbsp;&nbsp;&nbsp;&nbsp;Hingga kini belum ada obat yang dapat menyembuhkan buta warna, tapi bagaimanapun pengidap boleh diajar untuk menyesuaikan diri dalam mengatasi kelemahannya dalam membedakan warna, seperti dengan menghafal bentuk, ukuran. Untuk mengurangi gejala dapat digunakan kacamata yang berlensa dengan filter warna khusus yang memungkinkan pasien melakukan interpretasi warna kembali.</text>
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