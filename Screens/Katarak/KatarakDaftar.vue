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
      <text class="judul">I. DAFTAR PUSTAKA</text>


      <text class="paragraph list">https://www.alodokter.com/katarak-pada-manula
</text>
      <text class="paragraph list">https://www.alomedika.com/penyakit/oftalmologi/katarak/etiologi
</text>
      <text
        class="paragraph list"
      >Smeltzer,Suzanne. 2001. Buku Ajar Keperawatan Medikal Bedah Edisi 8 Volume 3. Jakarta; EGC
</text>
      <text
        class="paragraph list"
      >Mansjoer, Arief. 2001. Kapita Selekta Kedokteran Edisi 3 Jilid 1. Jakarta; Media Aesculapius Fakultas Kedokteran UI
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