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
      <text class="judul">ETIOLOGI</text>
      <text class="paragraph">- Bakteri</text>
      <text class="paragraph">- Klamidia</text>
      <text class="paragraph">- Virus</text>
      <text class="paragraph">- Jamur</text>
      <text class="paragraph">- Parasit (oleh bahan iritatif => kimia, suhu, radiasi) maupun imunologi (pada reaksi alergi).</text>
    </scroll-view>
  </view>
</template>



<style>
.thumb {
  align-items: center;
  padding-top: 20;
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
  text-align: justify;
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