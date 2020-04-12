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
      <text class="judul">PEMERIKSAAN DIAGNOSTIK</text>

      <text
        class="paragraph list"
      >1. Pemeriksaan Fisik: dimulai dengan pengukuran dan pencatatan ketajaman penglihatan menggunakan kartu Snellen dan indikator pengukur ketajaman penglihatan lain seperti cahaya dan gerak anggota tubuh.</text>
      <text
        class="paragraph list"
      >2. Slit lamp : untuk melihat kedalaman cedera di segmen anterior bola mata.</text>
      <text
        class="paragraph list"
      >3. Tes fluoresin : digunakan untuk mewarnai kornea, sehingga cedera kelihatan jelas.</text>
      <text class="paragraph list">4. Tonometri : untuk mengetahui tekakan bola mata.</text>
      <text
        class="paragraph list"
      >5. Pemeriksaan fundus yang didilatasikan dengan oftalmoskop indirek : untuk mengetahui adanya benda asing intraokuler.</text>
      <text
        class="paragraph list"
      >6. Tes Seidel : untuk mengetahui adanya cairan yang keluar dari mata.</text>
      <text
        class="paragraph list"
      >7. Pemeriksaan CT-Scan dan USG B-scan : digunakan untuk mengetahui posisi benda asing.</text>
      <text
        class="paragraph list"
      >8. Electroretinography (ERG) : untuk mengetahui ada tidaknya degenerasi pada retina.</text>
      <text
        class="paragraph list"
      >9. Pengukuran tekanan IOL dengan tonography: mengkaji nilai normal tekanan bola mata (normal 12-25 mmHg).</text>
      <text
        class="paragraph list"
      >10. Pengkajian dengan menggunakan optalmoskop: mengkaji struktur internal dari okuler, papiledema, retina hemoragi.</text>
      <text
        class="paragraph list"
      >11. Pemeriksaan Radiologi : pemeriksaan radiologi pada trauma mata sangat membantu dalam menegakkan diagnosa, terutama bila ada benda asing.</text>
      <text
        class="paragraph list"
      >12. Kertas Lakmus : pada pemeriksaan ini sangat membantu dalam menegakkan diagnosa trauma asam atau basa.</text>
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
  padding-top: 10;
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