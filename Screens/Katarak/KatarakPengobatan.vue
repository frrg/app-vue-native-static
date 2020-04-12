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
    <text class="judul">F. PENGOBATAN</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;
      Operasi katarak merupakan satu-satunya penanganan katarak pada lansia. Namun keputusan untuk menjalani operasi mempertimbangkan terganggunya aktivitas sehari-hari atau tidak, seperti menyetir kendaraan atau membaca.
    </text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;
Dalam operasi katarak, lensa yang keruh akan diangkat dan diganti dengan lensa tiruan. Lensa tiruan ini terbuat dari plastik atau silikon, dan dapat digunakan untuk seumur hidup. Sedangkan pada kondisi di mana lensa tiruan tidak bisa dipasang, pasien harus mengenakan kacamata atau lensa kontak pasca operasi katarak untuk memperbaiki penglihatan.
</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;
Operasi katarak dilakukan dengan bius lokal agar mata menjadi mati rasa, dan biasanya tanpa rawat inap. Rasa tidak nyaman di mata umumnya dirasakan hingga beberapa hari pasca operasi. Pada pasien dengan katarak di kedua mata, operasi dilakukan secara terpisah hingga pasien sembuh dari operasi pertama, yaitu sekitar 6-12 minggu.
</text>
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
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>