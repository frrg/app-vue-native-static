<template>
  <view>
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
      <view class="container-header">
        <image
          class="img"
          :style="{ width:150,height:150 }"
          :source="require('./../../assets/butawarna.png')"
        />
      </view>
      <text class="judul">C. KLASIFIKASI</text>

      <text
        class="paragraph"
      >&nbsp;&nbsp;&nbsp;Buta warna sendiri dapat diklasifikasikan menjadi 3 jenis yaitu trikromasi, dikromasi dan monokromasi. Trikomasi adalah perubahan sensitifitas warna dari satu jenis atau lebih sel kerucut. Dikromasi merupakan tidak adanya satu dari 3 jenis sel kerucut. Monokromasi ditandai dengan hilangnya atau berkurangnya semua penglihatan warna, sehingga yang terlihat hanya putih dan hitam pada jenis typical dan sedikit warna pada jenis atypical.</text>
      <text
        class="paragraph"
      >&nbsp;&nbsp;&nbsp;Buta warna dibagi dalam dua kategori, yaitu buta warna total dan buta warna parsial. Pada buta warna total, penyandangnya tidak bisa mengenali warna lain, kecuali hitam dan putih. Sementara itu, pada buta warna parsial, penyandang mengalami defisiensi (kekurangan) pigmen dalam sel retina sehingga tidak bisa melihat warna tertentu saja. Gabungan defisiensi merah dan hijau adalah gangguan yang paling sering terjadi, sedangkan defisiensi biru jarang sekali. Yang perlu diluruskan, penderita buta warna bukan tidak bisa mengenali satu warna tertentu, tetapi ia tak bisa mengenali kombinasi atau campuran warna. Ia bisa saja tahu warna-warna dasar, seperti kuning, merah, dan biru, serta warna-warna sekunder, seperti hijau, jingga, dan ungu. Namun, ketika warna-warna itu dikombinasikan lagi dengan warna lainnya, ia tidak mampu mengenali atau bingung menentukan, apakah itu hijau tua atau biru, dan sebagainya</text>
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