<template>
  <!-- 合作院校 -->
  <div class="estate">
    <pageHeader_M></pageHeader_M>
    <van-loading size="24px" color="gray" vertical v-if="!isShowContent"
      >加载中...</van-loading
    >

    <div v-if="this.$route.query.id === 1 && isShowContent">
      <div style="display: flex; justify-content: center;">
        <span
          style="font-size: 18px;color:burlywood;font-weight: bold;margin-bottom: 20px;margin-top: 10px;"
          >合作院校</span
        >
      </div>
      <img
        class="optionImg"
        style="width: 100%;height: 120px; display: block"
        src="../assets/0_common_M/hezuoyuanxiao.jpg"
        alt=""
      />
      <div class="content">
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >山东铝业职业学院</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/shandonglvye.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >滨州职业学院</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/binzhouzhiye.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >山东力明科技职业学院</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/shandongliming.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >济宁职业技术学院</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/jiningzhiye.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >烟台春山技工学校</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/yantaichunshan.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >青岛中工技工学校</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/qingdaozhonggong.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >德州近博技工学校
          </span>
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/dezhoujinbo.png"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >山东深泉技师学院</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/shandongshenquan.jpg"
            alt=""
          />
        </div>
        <div class="picText">
          <span style="font-size: 14px;color:burlywood;font-weight: bold;"
            >威海高级技工学校</span
          >
          <img
            width="100%;"
            height="160px"
            style="margin-top: 10px;"
            src="../assets/0_common_M/weihaigaoji.png"
            alt=""
          />
        </div>
      </div>
    </div>
    <div v-if="this.$route.query.id === 2 && isShowContent">
      <!-- <img
        width="100%"
        height="100px"
        src="../assets/0_common/page_nav_back_old.png"
        alt=""
      /> -->
      <!-- 视频部分 -->

      <div style="padding:10px">
        <span
          style="display: block;margin-top: 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top: 6px;"
        >
          焜曦教育集团自<span
            style="color:red;font-size: 16px;font-weight: 800;"
            >2012</span
          >年起，十几年来，一直专注于<span
            style="color:red;font-size: 16px;font-weight: 800;"
            >工业机器人技术人才的培养</span
          >，通过深入有效的校企合作，打通<span
            style="color:rgb(1,176,240);font-size: 16px;font-weight: 800;"
            >产业链、创新链、教育链、人才链</span
          >，在<span
            style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
            >济南、青岛、淄博、德州、威海、泰安、济宁、烟台、潍坊、石家庄、西安</span
          >等地设立培训基地.</span
        >
        <br />
        <span
          style="display: block; color: #616161;opacity: 0.8;font-weight: 700;padding-top: 6px;"
        >
          焜曦教育拥有经验丰富的<span
            style="color:red;font-size: 16px;font-weight: 800;"
            >双师型教授</span
          >手把手教课，开发<span
            style="color:red;font-size: 16px;font-weight: 800;"
            >独立的课程体系</span
          >，采用<span style="color:red;font-size: 16px;font-weight: 800;"
            >理论、仿真、实操</span
          >相结合的项目式教学模式,坚定不移的融入地方办学，深化产教融合、强化校企协同创新，已与<span
            style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
            >200余家企业单位</span
          >和<span style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
            >30家大、中专院校</span
          >建立合作，建成校内<span
            style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
            >实训基地50余个</span
          >，培养专业技能人才<span
            style="color:red;font-size: 16px;font-weight: 800;"
            >数十余万</span
          >人，人才培养供不应求，就业率达<span
            style="color:red;font-size: 18px;font-weight: 800;"
            >100%</span
          >。
        </span>
        <br />
        <div class="video-container">
          <video width="100%" controls>
            <source src="../assets/Timelapse_Crown.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
        <span
          style="display: block;margin: 10px 0 30px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
        >
          走出了一条具有自身特色的<span
            style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
            >技能型、高水平、促就业</span
          >的发展道路，经过多年的发展，焜曦集团已成为集人工智能机器人<span
            style="color:red;font-size: 16px;font-weight: 800;"
            >研发、设计、生产、培训以及学历教育</span
          >于一体的综合性单位。
        </span>
        <br />
      </div>
    </div>
    <div class="estate3" v-if="this.$route.query.id === 3 && isShowContent">
      <div class="education-container">
        <!-- 学历教育部分 -->
        <div class="education-card">
          <div class="card-header">
            <h2>学历教育</h2>
            <div class="header-decoration"></div>
          </div>
          <div class="card-content">
            <div class="info-row">
              <span class="info-label">热门专业</span>
              <span class="info-value">工业机器人</span>
            </div>
            <div class="info-row">
              <span class="info-label">学习学制</span>
              <span class="info-value">三年制</span>
            </div>
            <div class="info-row">
              <span class="info-label">学习目标</span>
              <span class="info-value">取得大学学历（3+3、3+4升学培养）</span>
            </div>
            <div class="info-row">
              <span class="info-label">报名对象</span>
              <span class="info-value">应、往届初中毕业生</span>
            </div>
            <div class="info-row">
              <span class="info-label">要求年龄</span>
              <span class="info-value">15周岁以上</span>
            </div>
          </div>
        </div>

        <!-- 高级技工部分 -->
        <div class="education-card">
          <div class="card-header">
            <h2>高级技工</h2>
            <div class="header-decoration"></div>
          </div>
          <div class="card-content">
            <div class="sub-section">
              <h3>应届初中生</h3>
              <div class="info-row">
                <span class="info-label">学习学制</span>
                <span class="info-value">3+2高级技工</span>
              </div>
            </div>
            <div class="sub-section">
              <h3>应、往届高中、技工、中专毕业生</h3>
              <div class="info-row">
                <span class="info-label">学习学制</span>
                <span class="info-value">高中起点（3年制）</span>
              </div>
              <div class="info-row">
                <span class="info-label">学习目标</span>
                <span class="info-value">取得大学学历（3+3、3+4升学培养）</span>
              </div>
              <div class="info-row">
                <span class="info-label">报名对象</span>
                <span class="info-value">应、往届初中毕业生</span>
              </div>
              <div class="info-row">
                <span class="info-label">要求年龄</span>
                <span class="info-value">15周岁以上</span>
              </div>
            </div>
          </div>
        </div>

        <!-- 短期培训部分 -->
        <div class="education-card">
          <div class="card-header">
            <h2>短期培训</h2>
            <div class="header-decoration"></div>
          </div>
          <div class="card-content">
            <div class="info-row">
              <span class="info-label">培养专业</span>
              <span class="info-value">工业机器人</span>
            </div>
            <div class="info-row">
              <span class="info-label">培训时长</span>
              <span class="info-value">7—10个月</span>
            </div>
            <div class="info-row">
              <span class="info-label">培养内容</span>
              <span class="info-value">工业机器人的操作、安装、调试、维修、维护、编程和设计</span>
            </div>
            <div class="info-row">
              <span class="info-label">学习目标</span>
              <span class="info-value">高薪资、保对口就业</span>
            </div>
            <div class="info-row">
              <span class="info-label">招生对象</span>
              <span class="info-value">初中、中专、高中、大专、本科、退伍军人、社会青年</span>
            </div>
            <div class="info-row">
              <span class="info-label">要求年龄</span>
              <span class="info-value">17一28岁</span>
            </div>
          </div>
        </div>

        <!-- 机器人人才说明部分 -->
        <div class="robot-talent-card">
          <p>
            <span class="highlight">集团在工业机器人的人才培养</span>
            具备了独一无二的优势，本着"<span class="quote">优势互补、合作共赢</span>"的原则，共同培养
            <span class="highlight">工业机器人专业人才</span>，以满足企业急需且日益增长的
            <span class="highlight">工业机器人专业人才需求</span>。
          </p>
        </div>
      </div>
    </div>
    <div v-if="this.$route.query.id === 4 && isShowContent">
      <div class="presentation-container">
        <section class="slide">
          <h1 class="title">使命</h1>
          <div class="content">
            <div class="text-content">
              <h2>核心理念</h2>
              <p>培养兼具知识与技能的时代栋梁。</p>
            </div>
          </div>
        </section>

        <section class="slide">
          <h2 class="title">价值观</h2>
          <div class="content">
            <ul class="values-list">
              <li>
                <strong>育人至上：</strong>始终将学生发展放在首位，因材施教。
              </li>
              <li>
                <strong>专业精进：</strong
                >持续更新教学内容，提供高质量教育服务。
              </li>
              <li>
                <strong>诚信协作：</strong
                >秉承诚实守信原则，在各个环节保持真诚。
              </li>
            </ul>
          </div>
        </section>

        <section class="slide">
          <h2 class="title">愿景</h2>
          <div class="content">
            <p>
              成为教育领域的标杆，以卓越的教育质量和创新的教育模式，培养出优秀人才。
            </p>
          </div>
        </section>
      </div>
    </div>
    <contactUs v-if="this.$route.query.id === 5 && isShowContent"></contactUs>
    <!-- 校长介绍人工智能 -->
    <div
      style="padding: 10px;"
      v-if="this.$route.query.id === 6 && isShowContent"
    >
      <!-- 视频部分 -->
      <div class="video-container">
        <video width="100%" controls>
          <source src="../assets/校长介绍人工智能.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
      </div>
      <h3>教学模式</h3>
      <span
        style="display: block;margin: 0px 0 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
      >
        教学上采用<span style="color:red;font-size: 16px;font-weight: 800;"
          >"理论、仿真、实训"三位一体"</span
        >教学方式，学生能 学到真正的技术，掌握真正的技能。
      </span>
      <!-- 学校进行阶段性学习和测考，考试合格，进入下一个阶段的学习，考试不合格，继续本阶段学习，直到考试合格，包教包会。
 -->
      <span
        style="display: block;margin: 0px 0 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
      >
        学校进行<span style="color:red;font-size: 16px;font-weight: 800;"
          >阶段性学习和测考</span
        >，考试合格，进入下一个阶段的学习，考试不合格，继续本阶段学习，直到考试合格，<span
          style="color:red;font-size: 16px;font-weight: 800;"
          >包教包会</span
        >。
      </span>
      <!--  学习专业知识，掌握专业技能为主体，并开设了素质课、人文 素养教育、心理咨询、国学、礼仪、岗前培训、岗前面试以及体能训练等课程，使学生德、智、体全面发展。
 -->
      <span
        style="display: block;margin: 0px 0 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
      >
        学习专业知识，掌握专业技能为主体，并开设了<span
          style="color:red;font-size: 16px;font-weight: 800;"
          >素质课、人文
          素养教育、心理咨询、国学、礼仪、岗前培训、岗前面试以及体能训练</span
        >等课程，使学生德、智、体全面发展。
      </span>
      <h3>管理模式</h3>
      <!-- 教官与学生同吃同住，保证学生的安全和身心健康 -->
      <span
        style="display: block;margin: 0px 0 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
      >
        教官与学生<span
          style="color:rgb(1, 176, 240);font-size: 16px;font-weight: 800;"
          >同吃同住</span
        >，保证学生的安全和身心健康。
      </span>
      <!-- 学校坚持军事化和人性化管理相结合，家校联合，培养德才兼备的复合型人才。 -->
      <span
        style="display: block;margin: 0px 0 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
      >
        学校坚持<span
          style="color:rgb(1, 176, 240);font-size: 16px;font-weight: 800;"
          >军事化和人性化管理</span
        >相结合，家校联合，培养德才兼备的复合型人才。
      </span>
      <!-- 学校实施制度化和温情化相结合的管理模式，以学生为本的理念，学校开展各项活动，丰富校园生活。
 -->
      <span
        style="display: block;margin: 0px 0 10px; color: #616161;opacity: 0.8;font-weight: 700;padding-top:6px"
      >
        学校实施<span
          style="color:rgb(1, 176, 240);font-size: 16px;font-weight: 800;"
          >制度化和温情化</span
        >相结合的管理模式，以学生为本的理念，学校开展各项活动，丰富校园生活。
      </span>
    </div>
    <!-- 教师风采 -->
    <div
      style="padding: 10px;"
      v-if="this.$route.query.id === 7 && isShowContent"
    >
      <img width="100%" src="../assets/pic3.jpg" alt="" />
      <img width="100%" src="../assets/pic4.jpg" alt="" />
      <img width="100%" src="../assets/pic5.jpg" alt="" />
      <img width="100%" src="../assets/pic6.jpg" alt="" />
    </div>
    <!-- 学生风采 8 -->
    <div
      style="padding:10px"
      v-if="this.$route.query.id === 8 && isShowContent"
    >
      <div
        v-if="this.$route.query.id === 8 && isShowContent"
        style="padding: 10px;"
      >
        <!-- Tab 控制 -->
        <div class="tabs">
          <button @click="setActiveTab(1)" :class="{ active: activeTab === 1 }">
            听听学生真心话
          </button>
          <button @click="setActiveTab(2)" :class="{ active: activeTab === 2 }">
            学习风采
          </button>
          <button @click="setActiveTab(3)" :class="{ active: activeTab === 3 }">
            课余拉练风采
          </button>
          <button @click="setActiveTab(4)" :class="{ active: activeTab === 4 }">
            课余校内风采
          </button>
        </div>

        <!-- 视频展示 -->
        <div v-if="activeTab === 1" class="video-container">
          <video width="100%" controls>
            <source src="../assets/学生风采4.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
        <div v-if="activeTab === 1" class="video-container">
          <video width="100%" controls>
            <source src="../assets/学生风采5.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
        <div v-if="activeTab === 2" class="video-container">
          <video width="100%" controls>
            <source src="../assets/学生风采1.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
        <div v-if="activeTab === 3" class="video-container">
          <video width="100%" controls>
            <source src="../assets/学生风采3.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
        <div v-if="activeTab === 4" class="video-container">
          <video width="100%" controls>
            <source src="../assets/学生风采2.mp4" type="video/mp4" />
            Your browser does not support the video tag.
          </video>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import contactUs from "./contactUs.vue";
export default {
  name: "estate_m",
  components: {
    contactUs
  },
  data() {
    return {
      activeTab: 1, // 默认选中第一个视频
      isShowContent: false,
      isLoading: false
    };
  },
  watch: {
    "$route.query.id"(newId, oldId) {
      // 每当 id 改变时，更新 currentId
      console.log(`ID changed from ${oldId} to ${newId}`);
    }
  },
  methods: {
    setActiveTab(tabIndex) {
      this.activeTab = tabIndex; // 切换视频
    }
  },
  mounted() {
    if (this.$route.query.id) {
      setTimeout(() => {
        this.isShowContent = true;
      }, 600);
    }
  }
};
</script>

<style lang="scss" scoped>
.tabs {
  display: flex;
  justify-content: space-between;
  width: 100%;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

.tabs button {
  flex: 1; /* 使按钮占满整个可用宽度 */
  padding: 10px;
  background-color: #f0f0f0;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin: 5px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s, transform 0.3s;
}

.tabs button:hover {
  background-color: #e0e0e0;
  transform: scale(1.05);
}

.tabs button.active {
  background-color: #007bff;
  color: white;
  border-color: #0056b3;
}

.tabs button:focus {
  outline: none;
}

.video-container {
  margin-bottom: 20px;
}
.van-loading {
  margin-top: 50%;
}
/* 容器样式 */
.robot-talent {
  font-family: "Arial", sans-serif;
  background-color: #f0f4f7;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  max-width: 800px;
  margin: 30px auto;
  text-align: center;
}

/* 段落样式 */
.robot-talent p {
  font-size: 16px;
  color: #34495e;
  line-height: 1.6;
}

/* 强调的文本样式 */
.highlight {
  color: #000099;
  font-weight: 600;
  text-decoration: underline;
}

/* 引用的文本样式 */
.quote {
  color: #e67e22;
  font-weight: 600;
  font-style: italic;
}

/* 响应式样式：小屏设备 */
@media screen and (max-width: 600px) {
  .robot-talent {
    padding: 20px;
    max-width: 100%;
  }

  .robot-talent p {
    font-size: 14px;
  }

  .highlight {
    font-size: 14px;
  }

  .quote {
    font-size: 14px;
  }
}

.content {
  padding: 0 10px;
  margin-top: 10px;
}
.content p {
  font-size: 18px;
}
.picText {
  margin-bottom: 30px;
  width: 100%;
}
/* 样式重置 */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* 标题样式 */
.heading {
  font-size: 26px;
  font-weight: 700;
  color: #2c3e50;
  margin-bottom: 20px;
  text-align: center;
}

/* 标签样式 */
.label {
  font-size: 16px;
  color: #7f8c8d;
  font-weight: 600;
  width: 120px;
  display: inline-block;
}

/* 内容样式 */
.value {
  font-size: 16px;
  color: #34495e;
  font-weight: 500;
  flex-grow: 1;
}

.estate3 {
  padding: 20px;
  background: linear-gradient(135deg, #f5f7fa 0%, #e4e8eb 100%);

  .education-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 30px;
  }

  .education-card {
    background: white;
    border-radius: 15px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);
    overflow: hidden;
    transition: transform 0.3s ease;

    &:hover {
      transform: translateY(-5px);
    }

    .card-header {
      background: linear-gradient(90deg, #2196F3, #1976D2);
      padding: 20px;
      position: relative;

      h2 {
        color: white;
        font-size: 24px;
        font-weight: 600;
        margin: 0;
      }

      .header-decoration {
        position: absolute;
        bottom: 0;
        left: 0;
        width: 100%;
        height: 4px;
        background: linear-gradient(90deg, #FFC107, #FF9800);
      }
    }

    .card-content {
      padding: 20px;
    }

    .sub-section {
      margin-bottom: 20px;
      
      h3 {
        color: #1976D2;
        font-size: 18px;
        margin-bottom: 15px;
        font-weight: 500;
      }
    }

    .info-row {
      display: flex;
      padding: 12px 0;
      border-bottom: 1px solid #f0f0f0;

      &:last-child {
        border-bottom: none;
      }

      .info-label {
        width: 120px;
        color: #666;
        font-weight: 500;
      }

      .info-value {
        flex: 1;
        color: #333;
      }
    }
  }

  .robot-talent-card {
    background: linear-gradient(135deg, #E3F2FD 0%, #BBDEFB 100%);
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.05);

    p {
      color: #333;
      line-height: 1.8;
      font-size: 16px;
      text-align: center;
    }

    .highlight {
      color: #1976D2;
      font-weight: 600;
    }

    .quote {
      color: #FF9800;
      font-style: italic;
    }
  }
}

@media (max-width: 768px) {
  .estate3 {
    padding: 10px;

    .education-card {
      .card-header h2 {
        font-size: 20px;
      }

      .info-row {
        flex-direction: column;
        gap: 5px;

        .info-label {
          width: 100%;
        }
      }
    }
  }
}

/* 响应式样式：小屏设备 */
@media screen and (max-width: 600px) {
  .education-info {
    padding: 20px;
    max-width: 100%;
  }

  .label {
    font-size: 14px;
    width: 120px;
  }

  .value {
    font-size: 14px;
  }
}
/* 样式容器 */
.presentation-container {
  display: flex;
  flex-direction: column;
  margin: 0 auto;
  width: 90%;
  max-width: 1200px;
  overflow: hidden;
  font-family: "Arial", sans-serif;
}

/* 幻灯片 */
.slide {
  padding: 50px 0 50px 80px;
  display: flex;
  flex-direction: row;
  margin: 20px 0;
  opacity: 0;
  animation: fadeIn 1s ease-out forwards;
  border-radius: 12px; /* 圆角效果 */
  box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1), 0 5px 10px rgba(0, 0, 0, 0.07); /* 大气阴影效果 */
  transition: all 0.3s ease-in-out; /* 平滑过渡 */
}

/* 标题样式 */
.title {
  font-size: 36px;
  font-weight: bold;
  color: #2c3e50;
  flex: 1;
  padding: 20px;
  text-align: left;
  background: linear-gradient(45deg, #3498db, #e74c3c);
  color: white;
  border-radius: 8px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
  text-transform: uppercase;
}

/* 内容区域 */
.content {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  width: 100%;
}

/* 图片样式 */
.slide-image {
  width: 40%;
  border-radius: 8px;
  box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
  transition: transform 0.5s ease-in-out;
}

/* 图片动画 */
.slide-image:hover {
  transform: scale(1.05);
}

/* 文本内容区域 */
.text-content {
  width: 50%;
  padding: 20px;
  font-size: 18px;
  color: #34495e;
}

/* 价值观列表 */
.values-list {
  list-style: none;
  padding-left: 0;
}

.values-list li {
  font-size: 18px;
  line-height: 1.8;
  margin-bottom: 12px;
}

.values-list strong {
  color: #e67e22;
}

/* 动画效果 */
@keyframes fadeIn {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

/* 响应式设计 */
@media screen and (max-width: 768px) {
  .presentation-container {
    width: 100%;
  }

  .content {
    flex-direction: column;
    align-items: center;
  }

  .slide-image {
    width: 80%;
    margin-bottom: 20px;
  }

  .text-content {
    width: 80%;
    text-align: center;
  }

  .title {
    font-size: 28px;
    padding: 15px;
  }
}

/* 视频部分样式 */
.video-container {
  margin: 30px 0;
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
