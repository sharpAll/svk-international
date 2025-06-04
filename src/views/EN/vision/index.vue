<template>
  <div class="block">
    <el-divider>
      <div class="title">OUR VISION</div>
    </el-divider>
    <div class="title-1">
      <p style="padding:0 40px">
        Illuminate policies with evidence to evaluate and drive change, providing theoretical foundations for more efficient and scientific major decisions.
      </p>
    </div>
    <div class="center-box" style="width:100%">
      <img
        style="margin:auto"
        width="100%"
        src="../../../assets/img/vision/vision-1.jpg"
      />
    </div>
    <el-divider>
      <div class="title">OUR MISSION</div>
    </el-divider>
    <div class="title-1">
      <p>
        Committed to becoming the preferred consulting service partner for clients
      </p>
      <p>
        Committed to enabling excellent enterprises to find the most suitable platform and opportunities for realizing their value
      </p>
      <p>
        Committed to building the best team of expert consultants
      </p>
    </div>
    <div class="center-box" style="width:100%">
      <img
        style="margin:auto"
        width="100%"
        src="../../../assets/img/vision/vision-2.jpg"
      />
    </div>
    <el-divider>
      <div class="title">OUR ADVANTAGES</div>
    </el-divider>
    <div class="center-box">
      <div class="bg-box" style="height:500px">
        <div class="vision-content">
          <div class="vision-title">Policy Evaluation Leader</div>
          <p>
            SVK is proficient in and flexible in applying mainstream policy evaluation frameworks both domestically and internationally (such as OECD-DAC standards, Theory Driven Evaluation, Realist Evaluation, Contribution Analysis), and can customize evaluation plans based on project characteristics.
          </p>
        </div>
        <div class="vision-content">
          <div class="vision-title">Rich Professional Experience</div>
          <p>
            The SVK professional consulting team has an average of over 5 years of experience in the consulting industry and has undergone professional and systematic skills training within SVK, strictly following standard workflows. Having a practical background in the industry they specialize in is the unique advantage of the SVK team, which enables them to gain a deeper understanding of their industry and provide more accurate services to clients and candidates.
          </p>
        </div>
        <div class="vision-content">
          <div class="vision-title">Focus On Vertical Fields</div>
          <p>
            SVK's consultants are divided into more than ten teams based on industry, each dedicated to delving into the vertical segmentation areas of their respective industries, fully grasping the current situation and trends of the industry, accurately positioning the market, and striving to provide more professional, efficient, and tailored services to meet the needs of enterprises.
          </p>
        </div>
        <div style="position:absolute;right:0;top:0;overflow:hidden">
          <img
            width="460px"
            height="500px"
            src="../../../assets/img/vision/vision-4.jpg"
          />
        </div>
      </div>
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
.title-1 {
  margin: 20px auto;
  font-size: 16px;
  color: #bbb;
  text-align: center;
}
.title-1 p {
  line-height: 25px;
}
.bg-box {
  background-color: #f9f9f9;
  position: relative;
  margin-top: 40px;
}
.bg-box .vision-title {
  font-size: 20px;
  padding-left: 30px;
  text-align: left;
  position: relative;
  margin-bottom: 10px;
}
.bg-box .vision-title::after {
  content: "";
  display: block;
  width: 3px;
  height: 18px;
  background: #606ecd;
  left: 0;
  top: 5px;
  position: absolute;
}
.bg-box .vision-content {
  margin-right: 470px;
  padding: 20px 0px 0 20px;
  height: auto;
}
.bg-box .vision-content.right {
  margin-right: 0;
  margin-left: 500px;
}
.bg-box .vision-content p {
  line-height: 24px;
  color: #888;
  font-size: 15px;
}
</style>
