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
      &nbsp;&nbsp;&nbsp;&nbsp;Trauma mata adalah tindakan sengaja maupun tidak yang menimbulkan perlukaan mata dan merupakan kasus gawat darurat mata.Perlukaan yang ditimbulkan dapat ringan sampai berat atau menimbulkan kebutaan bahkan kehilangan mata(Sidarta, 2005).
    </text>
    <text class="paragraph">
      &nbsp;&nbsp;&nbsp;&nbsp;Trauma mata adalah kondisi mata yang mengalami trauma (rudapaksa) baik oleh zat kimia maupun oleh benda keras dan tajam (Anas, 2010).
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