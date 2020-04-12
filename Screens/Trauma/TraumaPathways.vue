<template>
  <view>
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
    <text class="judul">E. PATHWAYS</text>
    
    <view class="thumb">
    <image
        :style="{ width:400,height:230}"
        :source="require('./../../assets/trauma/pathways-trauma.png')"
      />
  </view>
    </scroll-view>
  </view>
</template>

<style>

.thumb {
  align-items: center;
  padding-top:20;
}
.judul {
  font-size: 20;
  padding-left: 20;
  padding-bottom: 22;
  font-weight: bold;
}
.container-header {
  align-items: center;
  margin: 10;
}
.img {
  border-radius: 100;
}
</style>