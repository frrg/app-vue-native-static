<template>
  <view class="container">
    <view class="container-judul">
      <text class="judul b">Kelompok 6</text>
      <text class="judul">Kelas 2A3 International Class</text>
      <text class="judul">2020</text>
      <text class="keterangan">Heny Tri Suryani (P1337420618010)</text>
      <text class="keterangan">Fazanisa Zulfa Izzati (P1337420618040)</text>
      <text class="keterangan">Sinta Widhi Kurniawati (P1337420618063)</text>
      <text class="keterangan">Sonia Laila Maghfiroh (P1337420618072)</text>
      <text class="keterangan">Novia Anggi Astuti (P1337420618074)</text>
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
.keterangan {
  font-size: 16;
  color: black;
}
.home {
  margin:30;
  justify-content: center;
}
.b {
  font-weight: bold;
}
.judul {
  font-size: 20;
  color: darkolivegreen;
}
.container-judul {
  margin-top:10;
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