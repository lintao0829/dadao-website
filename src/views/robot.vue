<template>
  <div class="robot">
    <pageHeader_M></pageHeader_M>
    <img width="100%" src="../assets/pic1.jpg" alt="" />
    <!-- 视频部分 -->
    <div class="video-container">
      <video width="100%" controls>
        <source src="../assets/87_1742279409.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
    </div>
    <img width="100%" src="../assets/pic2.jpg" alt="" />
    <!-- 图片部分 -->
    <div class="image-container">
      <img
        width="100%"
        src="../assets/0_common_M/saomiaojian.png"
        alt="Image"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "robot"
};
</script>

<style scoped>
.robot {
  font-family: Arial, sans-serif;
  padding: 20px;
  background-color: #f9f9f9;
}

/* 图片部分样式 */
.image-container {
  margin-top: 20px;
  text-align: center;
}

/* 视频部分样式 */
.video-container {
  margin-top: 30px;
  background-color: #000; /* 给视频添加黑色背景 */
  padding: 10px;
  border-radius: 10px; /* 给视频容器圆角 */
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2); /* 视频容器阴影效果 */
  text-align: center;
  position: relative;
  z-index: 1;
}

video {
  max-width: 100%;
  border-radius: 8px; /* 视频边角圆滑 */
}
</style>
