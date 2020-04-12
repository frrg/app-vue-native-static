<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
      <view class="container-header">
        <image
          class="img"
          :style="{ width:150,height:150 }"
          :source="require('./../../assets/glaukoma.png')"
        />
      </view>
      <text class="judul">I. SUMBER</text>

      <text class="paragraph list">1. Sidarta Ilyas, Ilmu Penyakit Mata, FKUI, 2000.</text>
      <text class="paragraph list">2. Long C Barbara. Medical surgical Nursing. 1996</text>
      <text
        class="paragraph list"
      >3. Doungoes, marilyn E, Rencana Asuhan Keperawatan : Pedoman Untuk Perencanaan Dan pendokumentasian perawatan pasien. Ed 3, EGC, Jakarta, 1999</text>
      <text
        class="paragraph list"
      >4. Pusat Data dan Informasi Kementrian Kesehatan RI Mengenai Glaukoma, 2019</text>
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