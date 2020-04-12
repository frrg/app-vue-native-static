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
      <text class="judul">KLASIFIKASI</text>

      <text class="paragraph">1. Trauma Mekanik</text>

      <text
        class="paragraph list"
      >a. Trauma Tumpul dapat menyebabkan cedera perforasi dan non perforasi.Pada mata dapat mengenai organ eksterna (orbita dan palpebra) atau interna (konjungtiva, kornea, iris atau badan silier, lensa, korpus vitreus, retina dan nervus optikus (N.II).</text>
      <text
        class="paragraph list"
      >b. Trauma Tajam: trauma pada mata akibat benda tajam atau benda asing yang masuk ke mata.</text>

      <text class="paragraph">2. Trauma Kimia/Khemis</text>

      <text
        class="paragraph list"
      >a. Trauma Kimia Asam: trauma pada mata akibat substansi yang bersifat asam.</text>
      <text
        class="paragraph list"
      >b. Trauma Kimia Basa: trauma pada mata akibat substansi yang bersifat basa.</text>

      <text class="paragraph">3. Trauma Fisis</text>

      <text
        class="paragraph list"
      >a. Trauma termal: misalnya panas api, listrik, sinar las, sinar matahari.</text>
      <text
        class="paragraph list"
      >b. Trauma bahan radioaktif: misalnya sinar radiasi bagi pekerja radiologi</text>
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