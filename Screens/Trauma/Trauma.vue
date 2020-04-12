<template>
  <view class="container">
    <scroll-view :content-container-style="{contentContainer: {
        paddingVertical: 20
    }}">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/trauma.png')"
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
        :on-press="() => handleKlasifikasi()"
        title="Klasifikasi"
        accessibility-label="Klasifikasi"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleTanda()"
        title="Tanda dan Gejala"
        accessibility-label="Tanda dan Gejala"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handlePathways()"
        title="PathWays"
        accessibility-label="PathWays"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleDiagnostik()"
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
        :on-press="() => handleDiagnosa()"
        title="DIAGNOSA KEPERAWATAN DAN INTERVENSI"
        accessibility-label="DIAGNOSA KEPERAWATAN DAN INTERVENSI"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleDaftar()"
        title="DAFTAR PUSTAKA"
        accessibility-label="DAFTAR PUSTAKA"
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
      this.navigation.navigate("TraumaDefinisi");
    },
    handleDiagnostik() {
      this.navigation.navigate("TraumaDiagnostik");
    },
    handleEtiologi() {
      this.navigation.navigate("TraumaEtiologi");
    },
    handleKlasifikasi() {
      this.navigation.navigate("TraumaKlasifikasi");
    },
    handleTanda() {
      this.navigation.navigate("TraumaTanda");
    },
    handlePathways() {
      this.navigation.navigate("TraumaPathways");
    },
    handlePengobatan() {
      this.navigation.navigate("TraumaPengobatan");
    },
    handleDiagnosa() {
      this.navigation.navigate("TraumaDiagnosa");
    },
    handleDaftar() {
      this.navigation.navigate("TraumaDaftar");
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