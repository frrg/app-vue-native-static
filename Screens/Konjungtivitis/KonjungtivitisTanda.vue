<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
      <view class="container-header">
        <image
          class="img"
          :style="{ width:150,height:150 }"
          :source="require('./../../assets/konjungtivitis.png')"
        />
      </view>
      <text class="judul">TANDA DAN GEJALA</text>
      <text class="paragraph">• Hyperemia (kemerahan)</text>
      <text class="paragraph">• Cairan</text>
      <text class="paragraph">• Edema</text>
      <text class="paragraph">• Pengeluaran air mata</text>
      <text class="paragraph">• Gatal</text>
      <text class="paragraph">
        <text class="bold">Komplikasi</text> dari konjungtivitis yang tidak tertangani diantaranya :
      </text>
      <text class="paragraph">• Glaukoma</text>
      <text class="paragraph">• Katarak</text>
      <text class="paragraph">• Ablasi retina</text>
      <text
        class="paragraph"
      >• Komplikasi pada konjungtivitis kataral teronik merupakan segala penyulit dari blefaritis seperti ekstropin, trikiasis.</text>
      <text
        class="paragraph"
      >• Komplikasi pada konjungtivitis purulenta adalah seringnya berupa ulkus kornea.</text>
      <text class="paragraph">• Komplikasi pada konjungtivitis membranasea dan psdeudomembranasea</text>
      <text class="paragraph">• Komplikasi konjungtivitis vernal.</text>
      <text class="paragraph">• Rasa terbakar/ rasa tercakar</text>
      <text class="paragraph">• Ada benda asing</text>
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
.bold {
  font-weight:bold;
}
.paragraph {
  font-size: 16;
  padding-left: 20;
  padding-right: 20;
  text-align: justify;
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