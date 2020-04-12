<template>
  <view class="con">
    <status-bar background-color="white" bar-style="dark-content" />
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-judul">
      <!-- <table></table> -->
      <text class="judul">GANGGUAN PADA SISTEM PENGLIHATAN</text>
    </view>
    <view class="container">
      <touchable-opacity :on-press="() => handleGlaukoma()">
        <view class="content">
          <image class="img" :style="{ width:150,height:150 }" :source="require('./assets/glaukoma.png')" />
          <text class="name">GLAUKOMA</text>
        </view>
      </touchable-opacity>
      <touchable-opacity :on-press="() => handleTrauma()">
      <view class="content">
        <image class="img" :style="{ width:150,height:150 }" :source="require('./assets/trauma.png')" />
        <text class="name">TRAUMA PADA MATA</text>
      </view>
      </touchable-opacity>
    </view>
    <view class="container">
      <touchable-opacity  :on-press="() => handleButaWarna()">
        <view class="content">
          <image class="img" :style="{ width:150,height:150 }" :source="require('./assets/butawarna.png')" />
          <text class="name">BUTA WARNA</text>
        </view>
      </touchable-opacity>
      <touchable-opacity :on-press="() => handleKonjungtivitis()">
        <view class="content">
          <image class="img" :style="{ width:150,height:150 }" :source="require('./assets/konjungtivitis.png')" />
          <text class="name">KONJUNGTIVITIS</text>
        </view>
      </touchable-opacity>
    </view>
    <view class="container">
      <touchable-opacity :on-press="() => handleKatarak()">
        <view class="content">
          <image class="img" :style="{ width:150,height:150 }" :source="require('./assets/katarak.png')" />
          <text class="name">KATARAK</text>
        </view>
      </touchable-opacity>
    </view>
    <view class="container">
      <button
        :on-press="() => handleAbout()"
        title="ABOUT"
        color="#841584"
        accessibility-label="ABOUT"
    />
    </view>
    </scroll-view>
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
      this.navigation.navigate("Glaukoma");
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
    },
    handleAbout() {
      this.navigation.navigate("About");
    }
  }
};
</script>
<style>
.con {
  flex:1;
}
.img {
  border-radius:10;
}
.container {
  flex-direction: row;
  padding-left : 20;
  padding-right : 20;
  margin : 10;
  max-width: 400;
  justify-content: center;
}
.content {
  margin-left: 10;
  margin-right: 10;
  justify-content: center;
  align-items: center;
  border-width:1;
  padding: 10;
  border-radius:10;
  background-color: #e0e0e0;
}
.name {
  color: black;
  font-weight: bold;
  margin-top: 5;
}
.container-judul {
  margin-top:10;
  align-items: center;
  justify-content: center;
}
.judul {
  font-size: 15;
  font-weight: bold;
}
</style>