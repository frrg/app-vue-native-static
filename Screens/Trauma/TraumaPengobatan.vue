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
    <text class="judul">PENGOBATAN</text>
    <text class="paragraph">1.	Penatalaksanaan sebelum tiba di RS, antara lain :</text>
<text class="paragraph list">a.	Mata tidak boleh dibebat dengan tekanandan diberikan perlindungan tanpa kontak.</text>
<text class="paragraph list">b.	Tidak boleh dilakukan manipulasi yangberlebihan dan penekanan bola mata.</text>
<text class="paragraph list">c.	Benda asing tidak boleh dikeluarkantanpa pemeriksaan lanjutan.</text>
<text class="paragraph list">d.	Sebaiknya pasien di puasakan untukmengantisipasi tindakan operasi.</text>
<text class="paragraph">2.  Penatalaksanaan di RS, antara lain :</text>
<text class="paragraph list">a.	Pemberian antibiotik spektrum luas</text>
<text class="paragraph list">b.	Pemberian obat sedasi, antiemetik, dananalgetik sesuai indikasi.</text>
<text class="paragraph list">c.	Pemberian toksoid tetanus sesuai indikasi.</text>
<text class="paragraph list">d.	Pengangkatan benda asing di kornea,konjungtiva atau intraokuler.</text>
<text class="paragraph list">e.	Tindakan pembedahan /penjahitan sesuaidengan kausa dan jenis cedera.</text>
<text class="paragraph list">f.	Sisa-sisa lensa dan darah dikeluarkandengan aspirasi dan irigasi mekanis atauvitrektomi.</text>
<text class="paragraph"> &nbsp;&nbsp;&nbsp;&nbsp;Kerusakan oleh trauma kimia lakukan irigasi daerah yang terkena trauma kimia untuk menghilangkan dan melarutkan bahan penyebab trauma. Penanganan sebelum dibawa ke RS(guyur mata dengan menggunakan air bersih setelah terkena trauma untuk meghilangkan bahan penyebab trauma)</text>

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

.list{
  padding-left:35;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>