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
      <text class="judul">E. MANIFESTASI KLINIK</text>

      <text class="paragraph">
        &nbsp;&nbsp;&nbsp;Didalam bola mata terdapat cairan (aquos humor) yang berfungsi untuk memberikan nutrisi pada organ dalam bola mata.
        Cairan ini diproduksi dan dikeluarkan kembali dalam siklus yang seimbang sehingga tekanan pada bola mata tetap terjaga normal.
        Pada mata penderita glaukoma, siklus cairan ini tidak seimbang dimana cairan diproduksi tetapi terdapat masalah dalam saluran pengeluaran.
        Hal ini menyebabkan tekanan pada bola mata meningkat sehingga terjadi penekanan pada papil saraf optik. (Pusdatin RI, 2019)
      </text>

      <view class="thumb">
        <image
          :style="{ width:300,height:210}"
          :source="require('./../../assets/glaukoma/manifestasi-glaukoma-1.png')"
        />
      </view>
      <view class="thumb">
        <image
          :style="{ width:300,height:210}"
          :source="require('./../../assets/glaukoma/manifestasi-glaukoma-2.png')"
        />
      </view>
      <view class="thumb">
        <image
          :style="{ width:300,height:210}"
          :source="require('./../../assets/glaukoma/manifestasi-glaukoma-3.png')"
        />
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