<template>
  <view>
    <status-bar background-color="white" bar-style="dark-content" />
    <view class="container-judul">
      <!-- <table></table> -->
      <text class="judul">GANGGUAN SISTEM PENGLIHATAN</text>
    </view>
    <view class="container">
      <touchable-opacity class :on-press="() => handleGlaukoma()">
        <view class="content">
          <image :style="{ width:150,height:150 }" :source="require('./assets/glaukoma.png')" />
          <text class="name">GLAUKOMA</text>
        </view>
      </touchable-opacity>
      <view class="content">
      <touchable-opacity class="" :on-press="() => handleTrauma()">
        <image :style="{ width:150,height:150 }" :source="require('./assets/trauma.png')" />
        <text class="name">TRAUMA PADA MATA</text>
      </view>
    </view>
    <view class="container">
      <touchable-opacity class :on-press="() => handleButaWarna()">
        <view class="content">
          <image :style="{ width:150,height:150 }" :source="require('./assets/butawarna.png')" />
          <text class="name">BUTA WARNA</text>
        </view>
      </touchable-opacity>
      <touchable-opacity class :on-press="() => handleKonjungtivitis()">
        <view class="content">
          <image :style="{ width:150,height:150 }" :source="require('./assets/konjungtivitis.png')" />
          <text class="name">KONJUNGTIVITIS</text>
        </view>
      </touchable-opacity>
    </view>
    <view class="container">
      <touchable-opacity class :on-press="() => handleKatarak()">
        <view class="content">
          <image :style="{ width:150,height:150 }" :source="require('./assets/katarak.png')" />
          <text class="name">KATARAK</text>
        </view>
      </touchable-opacity>
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
    handleGlaukoma() {
      this.navigation.navigate("Another");
    },
    handleTrauma() {
      this.navigation.navigate("Trauma");
    },
    handleButaWarna() {
      this.navigation.navigate("ButaWarna");
    },
    handleKonjungtivitis() {
      this.navigation.navigate("Konjungtivitis");
    },
    handleKatarak() {
      this.navigation.navigate("Katarak");
    }
  }
};
</script>
<style>
.container {
  flex-direction: row;
  padding: 20px;
  max-width: 400;
  justify-content: center;
}
.content {
  margin-top: 1;
  margin-bottom: 1;
  margin-left: 10;
  margin-right: 10;
  justify-content: center;
  align-items: center;
}
.container-judul {
  background-color: white;
  justify-content: center;
  align-items: center;
  width: 100%;
}
.name {
  color: blueviolet;
  font-weight: bold;
  margin-top: 5;
}
.judul {
  font-size: 19;
  justify-content: center;
  font-weight: bold;
}
</style>