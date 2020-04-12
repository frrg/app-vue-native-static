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
    <text class="judul">B. ETIOLOGI</text>
  
<text class="paragraph">1.	Kelainan bawaan</text>
<text class="paragraph list">Adanya gangguan proses perkembangan embrio saat dalam kandungan dan kelainan
  pada kromosos secara genetic dapat menimbulkan kekeruhan lensa saat lahir. Pada umumnya kelainan tidak
  hanya pada lensa tapi juga pada bagian tubuh yang lain sehingga berupa suatu sindrom.
</text>
<text class="paragraph">2.	Proses penuaan </text>
<text class="paragraph list">
Dengan menjadi tuanya seseorang maka lensa mata akan kekurangan air dan menjadi lebih padat.
Lensa akan menjadi keras pada bagian tengahnya, sehingga kemampuannya memfokuskan benda dekat berkurang.
Hal ini mulai terlihat pada usia 45 tahun dimana mulai timbul kesukaran melihat dekat (presbiopia).
Pada usia 60 tahun hampir 60% mulai mengalami katarak atau lensa keruh. 
</text>
<text class="paragraph">3.	Penyakit tertentu  misalnya diabetes, kerusakan retina yang diturunkan
  (retinitis pigmentosa), atau radang pada lapisan tengah mata (uveitis) 
</text>
<text class="paragraph">4.	Konsumsi obat obat tertentu </text>
<text class="paragraph list">Obat tertentu dapat mempercepat timbulnya katarak seperti betametason,
  klorokuin, klorpromazin, kortison, ergotamin, indometasin, medrison, neostigmin, pilokarpin dan
  beberapa obat lainnya. Steroid adalah salah satu obat yang paling sering menyebabkan katarak.
  Dilaporkan bahwa penggunaan steroid berkontribusi sebesar 4,7% dari total ekstraksi katarak.
</text>
<text class="paragraph">5.	Pernah mengalami cedera pada mata.</text>
<text class="paragraph">6.	Gaya hidup kurang sehat</text>
<text class="paragraph list">Gaya hidup seperti sering mengkonsumsi alcohol, efek racun dari merokok, dan gizi kurang vitamin E</text>

  
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