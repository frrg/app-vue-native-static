<template>
  <view class="container">
    <text class="judul">{{ navigation.getParam('country') }}</text>
    <text class="keterangan">Kasus : {{ navigation.getParam('cmt') }}</text>
    <text class="keterangan">Sembuh :{{ navigation.getParam('sdt') }}</text>
    <text class="keterangan">Meninggal :{{ navigation.getParam('fst') }}</text>

    <button title="Kembali" @press="() => navigation.goBack()" />
  </view>
</template>

<script>
export default {
  props: {
    navigation: {
      type: Object
    }
  }
};
</script>

<style>
.keterangan {
  font-size: 20;
  color: blue;
}
.judul {
  font-size: 30;
}

.container {
  background-color: white;
  flex: 1;
}
</style>