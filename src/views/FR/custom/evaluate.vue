<template>
  <div class="block">
    <el-divider>
      <div class="title">Ulasan Pelanggan</div>
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
                "Kami terkesan dengan pemahaman industri oleh tim konsultan SVK. Saya pikir mereka bukan hanya tim data profesional, tetapi juga penasihat yang baik untuk bisnis khusus kami. ”
              </p>
            </div>
            <div class="person-box">
              ——Perusahaan Manufaktur Mobil Internasional | Presiden
            </div>
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
                "SVK menawarkan program yang sangat kaya dan sesuai dengan kebutuhan kami, dengan sumber daya yang luas di pemerintah lokal dan komunitas bisnis di seluruh dunia. ”
              </p>
            </div>
            <div class="person-box">
              ——Perusahaan Konsultan Terbaik di Dunia
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
                "Wawasan profesional SVK mengesankan dan selalu memberikan dukungan tepat waktu dan efektif selama proses layanan kami. Kami akan tumbuh bersama SVK. Kami mempercayai mereka. ”
              </p>
            </div>
            <div class="person-box">
              ——Produsen industri asing besar | Direktur
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
                "Saya terkejut dengan pemahaman upaya SVK tentang industri, bisnis, dan mereka selalu aktif dan memberikan saran yang berharga. ”
              </p>
            </div>
            <div class="person-box">
              ——Perusahaan Kepala Perusahaan Aerospace China ｜General Manager
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
