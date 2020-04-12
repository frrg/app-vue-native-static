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
    <text class="judul">A. DEFINISI</text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Glaukoma adalah suatu penyakit yang memberikan gambaran klinik berupa peninggian tekanan bola mata,
      penggaungan papil saraf optik dengan defek lapang pandangan mata. (Sidarta Ilyas, 2000).
    </text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;
      Glaukoma adalah sekelompok kelainan mata yang ditandai dengan peningkatan tekanan intraokuler.( Long Barbara, 1996)
    </text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Jadi, Glaukoma merupakan penyakit kerusakan pada saraf mata yang menyebabkan menyempitnya lapangan pandang dan hilagnya fungsi penglihatan.
      Fakto resiko utama yang menyebabkan glaukoma adalah peningkatan pada bola mata. (Pusdatin RI, 2019)
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
.paragraph{
  font-size: 16;
  padding-left:20;
  padding-top:5;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>