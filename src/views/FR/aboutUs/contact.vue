<template>
  <div class="block">
    <el-divider>
      <div class="title">Hubungi Kami</div>
      <div class="title-1">
        Jika ada pertanyaan, silakan kirimkan email kepada kami untuk mendapatkan bantuan.
      </div>
    </el-divider>
    <div class="center-box">
      <div class="contact-box">
        <div class="box-item">
          <div class="icon icon-1"></div>
          <div class="info">
            <div class="info-title">Kerjasama perusahaan</div>
            <p>
              <span class="red">muhammad.ridwan.kamil@svk-idn.com</span>
            </p>
          </div>
        </div>
        <div class="box-item">
          <div class="icon icon-2"></div>
          <div class="info">
            <div class="info-title">Pencarian pekerjaan pribadi</div>
            <p>
              Silakan kirimkan resume Anda ke <span class="red">dewi.lestari@svk-idn.com</span> Jika ada posisi yang tepat, pemburu industri yang sesuai akan menghubungi Anda secara langsung.
            </p>
          </div>
        </div>
        <div class="box-item">
          <div class="icon icon-3"></div>
          <div class="info">
            <div class="info-title">Bergabunglah dengan kami</div>
            <p>
             Jika Anda ingin bergabung dengan SVK, hubungi <span class="red">putri.ayu.dewi@svk-idn.com</span> untuk informasi lebih lanjut.
            </p>
          </div>
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
  font-size: 14px;
  color: #ccc;
  text-align: center;
}
.contact-box {
  margin: 50px auto;
  width: 660px;
}
.contact-box .box-item {
  position: relative;
  background-color: #f9f9f9;
  height: 160px;
  margin-bottom: 30px;
}
.contact-box .box-item .info {
  padding-left: 220px;
  padding-right: 50px;
}
.contact-box .box-item .info .info-title {
  padding: 40px 0 15px;
  font-size: 20px;
  color: #333;
}
.contact-box .box-item .icon {
  position: absolute;
  width: 100px;
  height: 100px;
  top: 20px;
  left: 100px;
}
.contact-box .box-item .icon.icon-1 {
  background: url("../../../assets/img/aboutUs/icon-contact-company.png");
  background-size: cover;
}
.contact-box .box-item .icon.icon-2 {
  background: url("../../../assets/img/aboutUs/icon-contact-person.png");
  background-size: cover;
}
.contact-box .box-item .icon.icon-3 {
  background: url("../../../assets/img/aboutUs/icon-contact-joinus.png");
  background-size: cover;
}
.red {
  color: #ff0000;
}
</style>
