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
        :on-press="() => handleKlasifikasi()"
        title="Klasifikasi"
        accessibility-label="Klasifikasi"
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
        :on-press="() => handlePathways()"
        title="PathWays"
        accessibility-label="PathWays"
      />
    </view>
    <view class="content">
      <button
        :on-press="() => handleManifestasi()"
        title="Manifestasi Klinik"
        accessibility-label="Manifestasi Klinik"
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
        :on-press="() => handleDiagnosa()"
        title="DIAGNOSA KEPERAWATAN DAN INTERVENSI"
        accessibility-label="DIAGNOSA KEPERAWATAN DAN INTERVENSI"
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
        :on-press="() => handleSumber()"
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
      this.navigation.navigate("GlaukomaDefinisi");
    },
    handleDiagnostik() {
      this.navigation.navigate("GlaukomaDiagnostik");
    },
    handleEtiologi() {
      this.navigation.navigate("GlaukomaEtiologi");
    },
    handleKlasifikasi() {
      this.navigation.navigate("GlaukomaKlasifikasi");
    },
    handleManifestasi() {
      this.navigation.navigate("GlaukomaManifestasi");
    },
    handlePathways() {
      this.navigation.navigate("GlaukomaPathways");
    },
    handlePengobatan() {
      this.navigation.navigate("GlaukomaPengobatan");
    },
    handleDiagnosa() {
      this.navigation.navigate("GlaukomaDiagnosa");
    },
    handleSumber() {
      this.navigation.navigate("GlaukomaSumber");
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