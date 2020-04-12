<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/konjungtivitis.png')"
      />
    </view>
    <text class="judul">DEFINISI</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Konjungtivitis merupakan peradangan pada konjungtiva (lapisan luar mata dan
      lapisan dalam kelopak mata) yang disebabkan oleh mikroorganisme (virus, bakteri, jamur), alergi, dan iritasi bahan-bahan kimia. (Mansjoer, Arif dkk: 2001)
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