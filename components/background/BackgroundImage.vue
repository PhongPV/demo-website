<template>
  <div class="bg-container">
    <div class="describe">
      <p class="title">DigitalToken.io</p>
      <p class="description">The most advanced responsive front-end
          framework in the world.</p>
      <div class="button">
        <a href="#">Buying toolkit</a>
      </div>
      <div class="desc-github">
        <img
          src="../../assets/icons/Star.png"
          alt="star-icon"
          class="icon"/>
        <span class="text-desc">27.3k GitHub stars</span>
      </div>
      <div class="desc-author">
        <img
          src="../../assets/icons/Polygon.png"
          alt="polygon-icon"
          class="icon"/>
        <span class="text-desc">@phongpham</span>
      </div>
    </div>
    <img
      src="/images/background.png"
      alt=""
      class="bg-image"/>
  </div>
</template>

<style>
.bg-container {
  display: flex;
  justify-content: center;
  align-items: flex-end;
}
.bg-container .describe {
  position: absolute;
  padding-bottom: 70px;
  padding-left: 50px;
}
.bg-container .describe .title {
  color: #fff;
  font-size: 50px;
  margin-bottom: 10px;
}
.bg-container .describe .description {
  color: #fff;
  font-size: 20px;
  font-weight: 100;
  margin-bottom: 15px;
  width: 400px;
}
.bg-container .describe .button {
  background-color: #0080ff;
  width: 200px;
  height: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 20px;
}
.bg-container .describe .button a {
  color: #fff;
  font-size: 17px;
  font-weight: bold;
  text-decoration: none;
}
.bg-container .describe .desc-author {
  display: flex;
  align-items: center;
  margin-bottom: 50px;
}
.bg-container .describe .desc-github {
  display: flex;
  align-items: center;
}
.bg-container .describe .text-desc {
  color: #fff;
  margin-left: 5px;
  font-size: 15px;
  font-weight: 100;
}
.bg-container .describe .icon {
  width: 12px;
}
</style>
