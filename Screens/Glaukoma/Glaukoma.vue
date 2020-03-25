<template>
  <view class="container">
    <view class="container-header">
      <image
        class="img"
        :style="{ width:150,height:150 }"
        :source="require('./../../assets/glaukoma.png')"
      />
    </view>
    <view class="container">
      <button class="btn"
        :on-press="() => handleDeskripsi()"
        title="Deskripsi"
        color="#e0e0e0"
        accessibility-label="Deskripsi"
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
    handleDeskripsi() {
      this.navigation.navigate("GlaukomaDeskripsi");
    }
  }
};
</script>

<style>
.btn {
  color: black;
}
.container {
  background-color: white;
  flex: 1;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>