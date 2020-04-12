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
    <text class="judul">B. KLASIFIKASI</text>
    <text class="paragraph">Klasifikasi Glaukoma, yaitu :</text>

    <text class="paragraph list">
      1. Glaukoma primer adalah glaukoma yang tidak diketahui penyebabnya. Glaukoma primer sudut terbuka (primary open angle glaucoma) biasanya merupakan glaukoma kronis. Glaukoma primer sudut tertutup (primary angle closure glaucoma) bisa berupa akut atau kronis
    </text>
    <text class="paragraph list">
      2. Glaukoma sekunder adalah glaukoma yang timbul sebagai akibat dari penyakit mata lain, trauma, pembedahan, penggunaan kortikosteroid yang berlebihan atau penyakit sistemik lainnya.
      </text>
    <text class="paragraph list">
      3. Glaukoma kongenital adalah glaukoma yang ditemukan sejak dilahirkan, dan biasanya disebabkan oleh sistem saluran pembuangan didalam mata tidak berfungsi dengan baik sehingga menyebabkan pembesaran mata bayi
      </text>
    <text class="paragraph list">
      4. Glaukoma absolut adalah glaukoma dengan kebutaan total
    </text>
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
  padding-right: 20;
  text-align:justify;
  padding-top: 5;
}
.list {
  padding-left:30;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>