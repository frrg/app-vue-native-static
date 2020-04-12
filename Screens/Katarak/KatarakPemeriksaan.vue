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
      <text class="judul">E. PEMERIKSAAN DIAGNOSTIK</text>

<text class="paragraph">Untuk memperoleh diagnosis katarak, dokter mata akan menanyakan riwayat penyakit
  dan gejala apa saja yang dialami pasien. Kemudian, dokter akan melakukan pemeriksaan pada mata pasien,
  diikuti dengan pemeriksaan penunjang seperti:
</text>
<text class="paragraph list">•	<text class="bold">Tes ketajaman penglihatan.</text> Dalam tes ini,
pasien akan diminta membaca huruf dalam jarak 6 meter menggunakan satu mata, di mana di saat yang sama mata
yang lain akan ditutup. Huruf yang ditampilkan akan semakin mengecil, hingga pasien tidak bisa membacanya
dengan jelas.
</text>
<text class="paragraph list">•	<text class="bold">Pemeriksaan <text class="italic">slit-lamp</text>
(lampu celah).</text> Pemeriksaan slit-lamp menggunakan mikroskop khusus yang dilengkapi cahaya untuk
menerangi lensa, iris, dan kornea mata. Cahaya ini akan membantu dokter melihat kelainan pada mata dengan
lebih jelas.
</text>
<text class="paragraph list">•	<text class="bold">Pemeriksaan retina mata.</text> Dilakukan dengan memberikan
obat tetes mata untuk membuat pupil membesar. Dengan bantuan alat khusus bernama oftalmoskop, dokter akan
lebih mudah melihat kondisi retina.
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