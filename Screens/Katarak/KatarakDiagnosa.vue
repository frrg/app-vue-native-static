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
      <text class="judul">H. DIAGNOSA KEPERAWATAN</text>
      <text class="paragraph bold">1. Pre Operasi</text>
 <text class="paragraph list">a.	Cemas (ansietas) berhubungan dengan kerusakan sensori dan kurangnya
   pemahaman mengenai tindakan operasi yang akan dilakukan.
 </text>
<text class="paragraph list">b.	Resiko Cedera berhubungan dengan kerusakan penglihatan.</text>
<text class="paragraph list">c.	Gangguan sensori persepsi: penglihatan berhubungan dengan gangguan
  penerimaan sensori/ perubahan status organ indera.
</text>
       <text class="paragraph bold">2. Post Operasi</text>
<text class="paragraph list">a.	Resiko tinggi terhadap infeksi berhubungan dengan prosedur invasive.</text>
<text class="paragraph list">b.	Gangguan sensori perceptual : penglihatan berhubungan dengan gangguan
  penerimaan sensori/ status organ indera.</text>
<text class="paragraph list">c.	Gangguan rasa nyaman: nyeri berhubungan dengan terputusnya kontinuitas
  jaringan pasca operasi.
</text>
<text class="paragraph list">d.	Resiko tinggi cedera berhubungan dengan kehilangan penglihatan
  perifer sementara dan persepsi sekunder terhadap pembedahan mata.
</text>
<text class="paragraph list">e.	Cemas (ansietas) berhubungan dengan perubahan status kesehatan.</text>
<text class="paragraph list">f.	Diagnosa Psikososial : Kurang pengetahuan berhubungan dengan keterbatasan
  sumber informasi.
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
  padding-right: 20;
  text-align:justify;
  padding-top: 5;
}
.list {
  padding-left: 40;
}
.container-header {
  align-items: center;
  margin: 10;
}
.bold {
  font-weight:bold;
}

.italic {
  font-style: italic;
}
.img {
  border-radius: 100;
}
</style>