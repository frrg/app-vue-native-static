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
      <text class="judul">F. PEMERIKSAAN DIAGNOSTIK</text>
      <text class="paragraph">
        Pemeriksaan yang dilakukan dalam menegakkan diagnosa glaucoma diantaranya :</text>

      <text class="paragraph list">
        1. Pemeriksaan tekanan bola mata dengan tes tonometry. Proses pemeriksaan ini adalah dengan menyentuh sebagian kecil bola mata atau dengan semburan udara.</text>
      <text class="paragraph list">
        2. Evaluasi struktur mata. Pemeriksaan ini dilakukan dengan menggunakan obat tetes midriasil untuk melebarkan pupil sehingga detail saraf mata dapat terlihat dengan jelas</text>
      <text class="paragraph list">
        3. Pemeriksaan luas lapangan pandang dengan tes perimetri. Pemeriksaan ini dilakukan untuk melihat luas penglihatan berupa pemetaar daerah yang bisa dilihat oleh pasien.</text>
      <text class="paragraph list">
        4. Pemeriksaan sudut bilik mata depan dengan tes gonioskopi. Pemeriksaan dilakukan dengan mengqunakan lensa kontak gonioskopi vang ditempelkan pada bola mata</text>
      <text class="paragraph list">
        5. Pemeriksaan ketebalan kornea mata dengan tes pakimetri. Pakimetri bertujuan untuk mengukur ketebalan kornea yaitu jaringan bening yang berada paling depan dari bola mata.</text>
      <text class="paragraph">
        &nbsp;&nbsp;&nbsp;&nbsp;
        (Pusdatin RI, 2019)
      </text>
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