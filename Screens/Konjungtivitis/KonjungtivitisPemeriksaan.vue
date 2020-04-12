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
      <text class="judul">PEMERIKSAAN</text>
      <text class="paragraph">
        &nbsp;&nbsp;&nbsp;Pemeriksaan penunjang untuk menegakkan diagnosa konjungtivitis sebenarnya cukup dengan anamnese
        dan pemeriksaan fisik, tetapi untuk meyakinkan maka diperlukan Pemeriksaan secara langsung dari
        kerokan atau getah mata setelah bahan tersebut dibuat sediaan yang dicat dengan pengecatan gram
        atau giemsa dapat dijumpai sel-sel radang polimorfonuklear. Pada konjungtivitis yang disebabkan
        alergi pada pengecatan dengan giemsa akan didapatkan sel-sel eosinofil.</text>
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