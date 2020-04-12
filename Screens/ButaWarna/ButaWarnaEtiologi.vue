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
    <text class="judul">B. ETIOLOGI</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;Buta warna merupakan kelainan genetik yang diturunkan dari orang tua kepada anaknya, kelainan ini sering juga disebut sex linked, karena kelainan ini dibawa oleh kromosom X. Beberapa penyakit yang diturunkan seperti distrofi sel kerucut dan akromatopsia juga dapat menyebabkan seseorang menjadi buta warna. Buta warna dapat juga ditemukan pada penyakit makula, saraf optik, sedang pada kelainan retina ditemukan cacat relative penglihatan warna biru dan kuning sedang kelainan saraf optik memberikan kelainan melihat warna merah dan hijau
    </text>
    </scroll-view>
  </view>
  
</template>



<style>
.thumb {
  align-items: center;
  padding-top:20;
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
  padding-left:30;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>