<template>
  <view class="container">
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
        :on-press="() => handleManifestasi()"
        title="Manifestasi Klinis"
        accessibility-label="Manifestasi Klinis"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handlePemeriksaan()"
        title="Pemeriksaan Buta Warna"
        accessibility-label="Pemeriksaan Buta Warna"
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
        title="DIAGNOSA KEPERAWATAN"
        accessibility-label="DIAGNOSA KEPERAWATAN"
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
      this.navigation.navigate("ButaWarnaDefinisi");
    },
    handleEtiologi() {
      this.navigation.navigate("ButaWarnaEtiologi");
    },
    handleKlasifikasi() {
      this.navigation.navigate("ButaWarnaKlasifikasi");
    },
    handleManifestasi() {
      this.navigation.navigate("ButaWarnaManifestasi");
    },
    handlePengobatan() {
      this.navigation.navigate("ButaWarnaPengobatan");
    },
    handlePemeriksaan() {
      this.navigation.navigate("ButaWarnaPemeriksaan");
    },
    handleDiagnosa() {
      this.navigation.navigate("ButaWarnaDiagnosa");
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