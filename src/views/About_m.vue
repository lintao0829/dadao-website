<template>
  <div class="about">
    <pageHeader_M @sendIndex="getIndex"></pageHeader_M>
    <img
      class="optionImg"
      style="width: 100%; display: block"
      src="../assets/0_common_M/option.png"
      alt=""
    />
    <div class="content">
      <div class="intro">
        <p class="title">关于焜曦教育</p>
        <p class="title_EN">ABOUT KUN XI JIAO YU</p>
        <div style="padding:10px 0">
          <span style="color: #616161;opacity: 0.8;font-weight: 700;">
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
          <span style="color: #616161;opacity: 0.8;font-weight: 700;">
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
            >和<span
              style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
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
          <span style="color: #616161;opacity: 0.8;font-weight: 700;">
            走出了一条具有自身特色的<span
              style="color:rgb(0,176,80);font-size: 16px;font-weight: 800;"
              >技能型、高水平、促就业</span
            >的发展道路，经过多年的发展，焜曦集团已成为集人工智能机器人<span
              style="color:red;font-size: 16px;font-weight: 800;"
              >研发、设计、生产、培训以及学历教育</span
            >于一体的综合性单位。
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "about",
  data() {
    return {
      navIndex: this.$route.params.navIndex,
      philosophy: [
        {
          img: require("../assets/2_about/icon1.png"),
          title: "企业定位",
          text: "成为城市商业产业服务的一流供应商。"
        },
        {
          img: require("../assets/2_about/icon2.png"),
          title: "企业文化",
          text: "与同道者同行，与同行者同享"
        },
        {
          img: require("../assets/2_about/icon3.png"),
          title: "企业信仰",
          text: "真诚、专注、极致、完美"
        }
      ]
    };
  },
  computed: {},
  props: {},
  components: {},
  mounted() {},
  methods: {
    getIndex(index) {
      this.navIndex = index;
    }
  }
};
</script>

<style scoped>
/* 介绍 */
.intro {
  padding: 40px 75px 0;
}

.intro .title {
  font-size: 30px;
  font-family: PingFang SC;
  font-weight: 800;
  color: #b69d74;
  margin-bottom: 16px;
}

.intro .title_EN {
  font-size: 32px;
  font-family: Roboto;
  font-weight: bold;
  color: #616161;
  opacity: 0.3;
  margin-bottom: 30px;
}

.intro .text {
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: bold;
  color: #616161;
  line-height: 40px;
  opacity: 0.8;
  margin-bottom: 24px;
}

/* 理念 */
.philosophy {
  padding: 40px 75px 0;
}

.philosophyBox {
  margin-bottom: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.philosophyBox img {
  width: 80px;
  height: 80px;
  display: block;
  margin-bottom: 15px;
}

.philosophyBox p.title {
  font-size: 26px;
  font-family: PingFang SC;
  font-weight: 800;
  color: #3d3d3d;
  margin-bottom: 15px;
}

/* 架构 */
.architecture img {
  width: 100%;
  display: block;
}
</style>
