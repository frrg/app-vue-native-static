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
      <text class="judul">G. DIAGNOSA KEPERAWATAN</text>
      <text class="paragraph">1. Gangguan persepsi warna</text>
      <text class="paragraph">2. Gangguan konsep diri</text>
      <text class="paragraph">3. Resiko terhadap cedera</text>
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