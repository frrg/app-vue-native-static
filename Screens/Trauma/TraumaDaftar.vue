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
      <text class="judul">DAFTAR PUSTAKA</text>

      <text
        class="paragraph list"
      >- Bachrudin,M.dkk.2016. Keperawatan Medikal Bedah I. Jakarta: Pusdik SDM Kesehatan</text>
      <text
        class="paragraph list"
      >- Smeltzer. Suzanne. C, Brenda G. Bare. 2001. Buku Ajar Keperawatan Medikal bedah Brunner & Suddarth Edisi 8 Volume 3 hal. 2015. EGC. Jakarta</text>
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