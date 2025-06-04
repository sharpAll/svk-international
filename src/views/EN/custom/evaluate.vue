<template>
  <div class="block">
    <el-divider>
      <div class="title">CLINETS’ EVALUATION</div>
    </el-divider>
    <div class="center-box">
      <el-row :gutter="60" style="margin-top:60px">
        <el-col :span="12">
          <div class="evaluate-box">
            <el-avatar
              :size="80"
              fit="cover"
              :src="require('../../../assets/img/custom/evaluate-1.jpg')"
            ></el-avatar>
            <div class="content-box">
              <p>
                "We are impressed by SVK's consulting team's understanding of the industry. I think they are not only a professional data team, but also good consultants for our specific business.”
              </p>
            </div>
            <div class="person-box">——International Auto-makers | CEO</div>
          </div>
        </el-col>
        <el-col :span="12">
          <div class="evaluate-box">
            <el-avatar
              :size="80"
              fit="cover"
              :src="require('../../../assets/img/custom/evaluate-2.jpg')"
            ></el-avatar>
            <div class="content-box">
              <p>
                "SVK provides us with extremely rich and tailored solutions that meet our needs, and they have extensive resources in local governments and business communities around the world."
              </p>
            </div>
            <div class="person-box">
              ——Global Top Consultancy Company | General Manager
            </div>
          </div>
        </el-col>
      </el-row>
      <el-row :gutter="60" style="margin-top:60px">
        <el-col :span="12">
          <div class="evaluate-box">
            <el-avatar
              :size="80"
              fit="cover"
              :src="require('../../../assets/img/custom/evaluate-3.jpg')"
            ></el-avatar>

            <div class="content-box">
              <p>
                "SVK's professional insight is impressive, providing us with timely and effective support throughout the service process. We will grow together with SVK. We trust them. ”
              </p>
            </div>
            <div class="person-box">
              ——Large-scale Foreign-invested Industrial Manufacturers | Director
            </div>
          </div>
        </el-col>
        <el-col :span="12">
          <div class="evaluate-box">
            <el-avatar
              :size="80"
              fit="cover"
              :src="require('../../../assets/img/custom/evaluate-4.jpg')"
            ></el-avatar>

            <div class="content-box">
              <p>
                "I was surprised by SVK's understanding of the industry and business, as they have always been proactive and provide valuable advice."
              </p>
            </div>
            <div class="person-box">
              ——Top-leading Aerospace Industry ｜General Manager
            </div>
          </div>
        </el-col>
      </el-row>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  }
};
</script>
<style scoped>
.title {
  font-size: 24px;
  color: #333;
  text-align: center;
}
.evaluate-box {
  position: relative;
}
.evaluate-box .el-avatar {
  position: absolute;
  left: 40px;
}
.evaluate-box .content-box {
  font-size: 17px;
  line-height: 25px;
  color: #312d2d;
  text-indent: 40px;
  padding: 15px 0 15px 160px;
  border-left: 5px solid #606ecd;
}
.evaluate-box .person-box {
  font-size: 17px;
  text-align: right;
  color: #333;
  padding-right: 20px;
  border-right: 5px solid #606ecd;
  margin-top: 20px;
}
</style>
