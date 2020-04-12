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
      <text class="judul">ETIOLOGI</text>

      <text
        class="paragraph list"
      >1. Trauma tumpul disebabkan akibat benturan mata dengan benda yang relatif besar, tumpul, keras maupun tidak keras misalnya terpukul, kena bola tenis, atau shutlecock, membuka tutup botol tidak dengan alat, ketapel.</text>
      <text
        class="paragraph list"
      >2. Trauma tajam ( Penetrating Injuries) disebabkan benda tajam atau benda asing yang masuk ke mata seperti kaca, logam, atau partikel kayu berkecepatan tinggi, percikan proses pengelasan, dan peluru.</text>
      <text
        class="paragraph list"
      >3. Trauma Khemis disebabkan akibat substansi yang bersifat asam dan alkali yang masuk ke mata.</text>
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