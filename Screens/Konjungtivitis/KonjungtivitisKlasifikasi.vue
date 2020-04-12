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
      <text class="judul">KLASIFIKASI</text>

      <text
        class="paragraph list"
      >• Konjungtivitis Bakteri terutama disebabkan oleh Staphylococcus aureus, Streptococcus pneumoniae,Haemophilus influenzae, dan Moraxella catarrhalis.</text>
      <text
        class="paragraph list"
      >• Konjungtivitis Viral. adalah akibat infeksi human adenovirus seperti Herpes simpleks, Herpes zoster Klamidia, New castle, Pikoma,Enterovirus, dan sebagainya atau dari penyakit virussistemik seperti mumps dan mononukleosis.</text>
      <text
        class="paragraph list"
      >• Konjungtivitis Alergi disebabkan oleh sensitivitas terhadap serbuk, protein hewani, bulu, makanan atau zat-zat tertentu, gigitan serangga dan/atauobat ( atropin dan antibiotik golongan Mycin.</text>
      <text
        class="paragraph list"
      >• Konjungtivitis blenore, konjungtivitis purulen ( bernanah pada bayi dan konjungtivitisgonore ). Penyebab oftalmia neonatorum adalah Gonococ, Chlamydia ( inklusion blenore ), StaphylococusMasa inkubasi bervariasi antara 3 – 6 hari, Gonore : 1 – 3 hari, Chlamydia : 5 – 12 hari</text>
   
    <view class="thumb">
    <image
        :style="{ width:170,height:410}"
        :source="require('./../../assets/konjungtivitis/gambar-1.png')"
      />
  </view>
    </scroll-view>
  </view>
</template>



<style>

.thumb {
  align-items: center;
  padding-top:20;
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