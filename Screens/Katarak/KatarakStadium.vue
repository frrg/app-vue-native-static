<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/katarak.png')"
      />
    </view>
    <text class="judul">D. STADIUM KATARAK</text>
    <text class="paragraph">1.	Katarak Insipien </text>
<text class="paragraph list">Kekeruhan lensa tahap awal dengan visus yang relatif masih baik
</text>
    <view class="thumb">
    <image
        :style="{ width:400,height:150}"
        :source="require('./../../assets/katarak/gambar-1.png')"
      />
  </view>
  <text class="paragraph">2.	Katarak Imatur </text>
<text class="paragraph list">Kekeruhan lensa mulai terjadi dapat terlihat oleh bantuan senter, terlihat iris shadow, visus > 1/60.
</text>
    <view class="thumb">
    <image
        :style="{ width:400,height:190}"
        :source="require('./../../assets/katarak/gambar-2.png')"
      />
  </view>
  <text class="paragraph">3.	Katarak Matur </text>
<text class="paragraph list">Kekeruhan lensa terjadi menyeluruh, dapat terlihat dengan bantuan senter, tidak terlihat iris shadow, visus 1/300 atau light perception positif
</text>
    <view class="thumb">
    <image
        :style="{ width:400,height:200}"
        :source="require('./../../assets/katarak/gambar-3.png')"
      />
  </view>
  <text class="paragraph">4.	Katarak hipermatur </text>
<text class="paragraph list">Katarak hipermatur terjadi ketika massa lensa mengalami kebocoran melalui kapsul lensa, sehingga kapsul menjadi berkerut dan menyusut
</text>
    <view class="thumb">
    <image
        :style="{ width:400,height:270}"
        :source="require('./../../assets/katarak/gambar-4.png')"
      />
  </view>
  <text class="paragraph">5.	Katarak Morgagnian </text>
<text class="paragraph list">Terjadi ketika pencairan korteks lensa berlanjut dan memungkinkan nucleus bergerak bebas dalam kantong kapsuler
</text>
    <view class="thumb">
    <image
        :style="{ width:400,height:260}"
        :source="require('./../../assets/katarak/gambar-5.png')"
      />
  </view>
  
  </scroll-view>
  </view>
  
</template>



<style>
.thumb {
  align-items: center;
  padding-bottom:20;
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