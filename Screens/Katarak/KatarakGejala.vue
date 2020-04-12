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
      <text class="judul">C. GEJALA</text>
<text class="paragraph">&nbsp;&nbsp;&nbsp;Katarak umumnya berkembang secara perlahan. Awalnya, penderita tidak akan
  menyadari ada gangguan penglihatan, karena hanya sebagian kecil lensa mata yang mengalami katarak.
  Namun seiring waktu, katarak akan memburuk dan memunculkan sejumlah gejala berikut:
</text>
<text class="paragraph list">•	Pandangan samar dan berkabut.</text>
<text class="paragraph list">•	Mata semakin sensitif saat melihat cahaya yang menyilaukan.</text>
<text class="paragraph list">•	Melihat lingkaran cahaya di sekeliling sumber cahaya.</text>
<text class="paragraph list">•	Sulit melihat dengan jelas saat malam hari.</text>
<text class="paragraph list">•	Warna terlihat pudar atau tidak cerah.</text>
<text class="paragraph list">•	Objek terlihat ganda.</text>
<text class="paragraph list">•	Ukuran lensa kacamata yang sering berubah.</text>
<text class="paragraph ">Meski umumnya katarak tidak menyebabkan rasa sakit pada mata, namun penderita
  bisa merasakan nyeri pada mata, terutama jika katarak yang dialami sudah parah, atau penderita memiliki
  gangguan lain pada mata.
</text>
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