<template>
  <view class="container">
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/glaukoma.png')"
      />
    </view>

    <view class="content">
      <button
        :on-press="() => handleDefinisi()"
        title="Definisi"
        accessibility-label="Definisi"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleEtiologi()"
        title="Etiologi"
        accessibility-label="Etiologi"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleGejala()"
        title="Gejala"
        accessibility-label="Gejala"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleStadium()"
        title="Stadium Katarak"
        accessibility-label="Stadium Katarak"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handlePemeriksaan()"
        title="Pemeriksaan Diagnostik"
        accessibility-label="Pemeriksaan Diagnostik"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handlePengobatan()"
        title="PENGOBATAN"
        accessibility-label="PENGOBATAN"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handlePathways()"
        title="Pathway"
        accessibility-label="Pathway"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleDiagnosa()"
        title="DIAGNOSA KEPERAWATAN"
        accessibility-label="DIAGNOSA KEPERAWATAN"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleDaftar()"
        title="SUMBER"
        accessibility-label="SUMBER"
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
    handleDefinisi() {
      this.navigation.navigate("KatarakDefinisi");
    },
    handlePemeriksaan() {
      this.navigation.navigate("KatarakPemeriksaan");
    },
    handleEtiologi() {
      this.navigation.navigate("KatarakEtiologi");
    },
    handleGejala() {
      this.navigation.navigate("KatarakGejala");
    },
    handlePathways() {
      this.navigation.navigate("KatarakPathways");
    },
    handlePengobatan() {
      this.navigation.navigate("KatarakPengobatan");
    },
    handleDiagnosa() {
      this.navigation.navigate("KatarakDiagnosa");
    },
    handleDaftar() {
      this.navigation.navigate("KatarakDaftar");
    }
  }
};
</script>

<style>
.container {
  background-color: white;
}
.content {
  padding:10;
}
.container-button {
  background-color: white;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>