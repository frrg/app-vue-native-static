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
      <text class="judul">E. PEMERIKSAAN BUTA WARNA</text>

      <text class="paragraph">1. Tes Ishihara (Gambar 1)</text>
      <text class="paragraph list">
        Dimana lingkaran-lingkaran berwarna yang beberapa diantaranya dirancang agar
        ada tulisan tertentu yang hanya dapat dilihat atau tidak dapat dilihat oleh penderita buta warna.
      </text>
      <text class="paragraph">2. Oftalmoskop (Gambar 2)</text>
      <text class="paragraph list">
        Suatu alat dengan system pencahayaan khusus, untuk melihat bagian dalam
        mata terutama retina dan struktur terkaitnya
      </text>
      <text class="paragraph">3. Uji pencocokan benang</text>
      <text class="paragraph list">
        Pasien diberi sebuah gelendong benang dan diminta untuk mengambil
        gelendong yang warnanya cocok dari setumpuk gelendong yang berwarna-warni.
      </text>
      <text class="paragraph">4. Tes sensitivitas kontras (Gambar 3)</text>
      <text class="paragraph list">5. Elektroretingrafi (ERG) (Gambar 4)</text>
      <text class="paragraph list">6. Elektro okulografi (EOG)</text>

       <view class="thumb">
        <image
          :style="{ width:300,height:210}"
          :source="require('./../../assets/butawarna/gambar-1.png')"
        />
        <text class="keterangan">Gambar 1</text>
      </view>
      <view class="thumb">
        <image
          :style="{ width:300,height:210}"
          :source="require('./../../assets/butawarna/gambar-2.png')"
        />
        <text class="keterangan">Gambar 2</text>
      </view>
      <view class="thumb">
        <image
          :style="{ width:300,height:390}"
          :source="require('./../../assets/butawarna/gambar-3.png')"
        />
        <text class="keterangan">Gambar 3</text>
      </view>
      <view class="thumb">
        <image
          :style="{ width:300,height:300}"
          :source="require('./../../assets/butawarna/gambar-4.png')"
        />
        <text class="keterangan">Gambar 4</text>
      </view>
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
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>