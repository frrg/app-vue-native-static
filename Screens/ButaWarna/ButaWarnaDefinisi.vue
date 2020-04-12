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
    <text class="judul">A. DEFINISI</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Buta warna adalah ketidakmampuan seseorang dalam membedakan warna ataupun ketidakmampuan seseorang dalam melihat warna yang disebabkan ketidakmampuan sel-sel kerucut (cone cell)  pada retina mata untuk menangkap suatu spektrum warna tertentu sehingga objek yang terlihat bukan warna yang sesungguhnya.
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
.paragraph{
  font-size: 16;
  padding-left:20;
  padding-right:20;
  text-align:justify;
  padding-top:5;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>