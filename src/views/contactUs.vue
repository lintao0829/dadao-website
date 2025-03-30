<template>
  <div class="contact-container">
    <div class="contact-header">
      <h1>联系我们</h1>
      <p>如有任何问题，欢迎与我们联系！</p>
    </div>

    <div class="contact-card">
      <div class="info-item">
        <div class="label">姓名：</div>
        <div class="value">焜曦教育-周老师</div>
      </div>

      <div class="info-item">
        <div class="label">电话：</div>
        <div class="value">+86 131 8897 1869</div>
      </div>

      <div class="info-item">
        <div class="label">地址：</div>
        <div class="value">青岛市城阳区棘洪滩街道荣海三路</div>
      </div>
    </div>

    <div class="wechat">
      <h2>微信加好友</h2>
      <p>扫描二维码添加我们微信，随时为您服务！</p>
      <div class="wechat-qrcode">
        <img src="@/assets/0_common/qrcode.jpg" alt="微信二维码" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactUs"
};
</script>

<style scoped>
.contact-container {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  background: #f8f9fa;
  color: #495057;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 40px;
}

.contact-header {
  text-align: center;
  margin-bottom: 40px;
}

.contact-header h1 {
  font-size: 40px; /* 2.5rem -> 40px */
  color: #b69d74;
  margin-bottom: 10px;
}

.contact-header p {
  font-size: 19px; /* 1.2rem -> 19px */
  color: #6c757d;
}

.contact-card {
  width: 100%;
  max-width: 600px;
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  padding: 20px;
  margin-bottom: 40px;
}

.info-item {
  display: flex;
  justify-content: space-between;
  padding: 12px;
  margin-bottom: 12px;
  border-bottom: 1px solid #f1f1f1;
}

.info-item:last-child {
  border-bottom: none;
}

.label {
  font-weight: 600;
  color: #b69d74;
}

.value {
  color: #495057;
}

.wechat {
  text-align: center;
  width: 100%;
}

.wechat h2 {
  font-size: 32px; /* 2rem -> 32px */
  color: #b69d74;
  margin-bottom: 15px;
}

.wechat p {
  font-size: 18px; /* 1.1rem -> 18px */
  color: #6c757d;
  margin-bottom: 20px;
}

.wechat-qrcode img {
  width: 280px;
  height: 300px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

@media (max-width: 768px) {
  .contact-container {
    padding: 20px;
  }

  .contact-header h1 {
    font-size: 32px; /* 2rem -> 32px */
  }

  .contact-header p {
    font-size: 16px; /* 1rem -> 16px */
  }

  .wechat h2 {
    font-size: 24px; /* 1.5rem -> 24px */
  }

  .wechat p {
    font-size: 16px; /* 1rem -> 16px */
  }

  .wechat-qrcode img {
    width: 300px;
    height: 340px;
  }
}
</style>
