<template>
  <view class="container">
    <view class="container-judul">
      <image class="img" :style="{ width:200,height:200 }" :source="require('./assets/logo.png')" />
      <text class="judul b">Kelompok 6:</text>
    </view>
    <view class="container-isi">
      <view class="content">
      <text class="keterangan">Heny Tri Suryani</text>
       <text class="keterangan npm">(P1337420618010)</text>
       </view>
      <view class="content">
      <text class="keterangan">Fazanisa Zulfa Izzati</text>
       <text class="keterangan npm">(P1337420618040)</text>
       </view>
       
      <view class="content">
      <text class="keterangan">Sinta Widhi Kurniawati</text>
       <text class="keterangan npm">(P1337420618063)</text>
       </view>
       
      <view class="content">
      <text class="keterangan">Sonia Laila Maghfiroh</text>
       <text class="keterangan npm">(P1337420618072)</text>
       </view>
       
      <view class="content">
      <text class="keterangan">Novia Anggi Astuti </text>
       <text class="keterangan npm">(P1337420618074)</text>
       </view>
      
    <view class="container-judul">
      <text class="center">Kelas 2A3 International Class</text>
      <text class="center">2020</text>
    </view>
    </view>
    <view class="home">
      <button
        :on-press="() => handleHome()"
        title="HOME"
        color="#841584"
        accessibility-label="HOME"
    />
    </view>
  </view>
</template>

<script>
export default {
  props: {
    navigation: {
      type: Object
    }
  },
  methods: {
    handleHome() {
      this.navigation.navigate("Main");
    }
  }
};
</script>

<style>

.content {
  flex-direction: row;
  max-width: 400;
  justify-content: center;
}

.keterangan {
  width: 190;
  color:#000;
  font-size:16;
  justify-content: center;
  align-items: center;
  padding-left: 10;
  padding-right: 10;
}
.npm {
  text-align:right;
}
.center {
  text-align:center;
  font-size: 16;
}
.home {
  margin:30;
  justify-content: center;
}
.b {
  font-weight: bold;
}
.judul {
  font-size: 16;
  padding : 30;
}
.container-judul {
  margin-top:10;
  align-items: center;
}
.container-body {
  margin-top:10;
}
.container {
  align-items: center;
  justify-content: center;
  /* background-color: #e0e0e0; */
  flex:1;
}
</style>