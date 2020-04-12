<template>
  <view class="container">
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
        :on-press="() => handlePemeriksaan()"
        title="Pemeriksaan"
        accessibility-label="Pemeriksaan"
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
        title="DIAGNOSA DAN INTERVENSI KEPERAWATAN"
        accessibility-label="DIAGNOSA DAN INTERVENSI KEPERAWATAN"
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
      this.navigation.navigate("KonjungtivitisDefinisi");
    },
    handlePemeriksaan() {
      this.navigation.navigate("KonjungtivitisPemeriksaan");
    },
    handleEtiologi() {
      this.navigation.navigate("KonjungtivitisEtiologi");
    },
    handleKlasifikasi() {
      this.navigation.navigate("KonjungtivitisKlasifikasi");
    },
    handleTanda() {
      this.navigation.navigate("KonjungtivitisTanda");
    },
    handlePengobatan() {
      this.navigation.navigate("KonjungtivitisPengobatan");
    },
    handleDiagnosa() {
      this.navigation.navigate("KonjungtivitisDiagnosa");
    },
    handleDaftar() {
      this.navigation.navigate("KonjungtivitisDaftar");
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