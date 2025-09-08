<template>
  <div class="block">
    <el-divider>
      <div class="title">Manufaktur Industri</div>
    </el-divider>
    <div class="trade-bg-box">
      <div class="trade-bg bg-1">
        <div class="trade-info">
          <span>Kimia & Bahan</span>
          <span>Energi</span>
          <span>Mobil</span>
          <span>Peralatan Otomatisasi</span>
          <span>Transportasi rel</span>
          <br/>
          <span>Muhammad Ridwan Kamil</span>
          <span>muhammad.ridwan.kamil@svk-idn.com</span>
        </div>
      </div>
    </div>
    <el-divider>
      <div class="title">Kesehatan Besar</div>
    </el-divider>
    <div class="trade-bg-box">
      <div class="trade-bg bg-2">
        <div class="trade-info">
          <span>farmasi</span>
          <span>Peralatan medis</span>
          <span>Layanan medis</span>
          <span>Kedokteran Klinis</span>
          <br/>
          <span>Dewi Lestari</span>
          <span>dewi.lestari@svk-idn.com</span>
        </div>
      </div>
    </div>
    <el-divider>
      <div class="title">Hukum</div>
    </el-divider>
    <div class="trade-bg-box">
      <div class="trade-bg bg-3">
        <div class="trade-info">
          <span>Penyelesaian perselisihan</span>
          <span>Hak kekayaan intelektual</span>
          <span>Merdekasi/Reorganisasi</span>
          <span>Hukum Kerja</span>
          <br/>
          <span>Putri Ayu Dewi</span>
          <span>putri.ayu.dewi@svk-idn.com</span>
        </div>
      </div>
    </div>
    <el-divider>
      <div class="title">Teknologi, Media dan Komunikasi</div>
    </el-divider>
    <div class="trade-bg-box">
      <div class="trade-bg bg-4">
        <div class="trade-info">
          <span>Internet seluler +</span>
          <span>Perdagangan Elektronik</span>
          <span>Internet Hal</span>
          <span>Permainan</span>
          <span>Keuangan Internet</span>
          <br/>
          <span>Siti Nurhaliza</span>
          <span>siti.nurhaliza@svk-idn.com</span>
        </div>
      </div>
    </div>
    <el-divider>
      <div class="title">Keuangan</div>
    </el-divider>
    <div class="trade-bg-box">
      <div class="trade-bg bg-5">
        <div class="trade-info">
          <span>Bank </span>
          <span>Sewa</span>
          <span>Asuransi</span>
          <span>Teknologi Keuangan</span>
          <span>Dana Sekuritas</span>
          <br/>
          <span>Rizki Pratama</span>
          <span>rizki.pratama@svk-idn.com</span>
        </div>
      </div>
    </div>
    <!-- <el-divider>
      <div class="title">Fungsi Perusahaan</div>
    </el-divider>
    <div class="trade-bg-box">
      <div class="trade-bg bg-6">
        <div class="trade-info">
          <span>Personel</span>
          <span>Hukum</span>
          <span>Keuangan</span>
          <span>Hubungan Masyarakat</span>
          <span>administrasi</span>
        </div>
      </div>
    </div> -->
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
.trade-bg-box {
  width: 100%;
  height: 200px;
  overflow: hidden;
}
.trade-bg-box .trade-bg {
  cursor: pointer;
  height: 200px;
}
.trade-bg-box .trade-bg.bg-1 {
  background: no-repeat url(../../../assets/img/trade/trade-1.jpg);
  background-size: cover;
}
.trade-bg-box .trade-bg.bg-2 {
  background: no-repeat url(../../../assets/img/trade/trade-2.jpg);
  background-size: cover;
}
.trade-bg-box .trade-bg.bg-3 {
  background: no-repeat url(../../../assets/img/trade/trade-3.jpg);
  background-size: cover;
}
.trade-bg-box .trade-bg.bg-4 {
  background: no-repeat url(../../../assets/img/trade/trade-4.jpg);
  background-size: cover;
}
.trade-bg-box .trade-bg.bg-5 {
  background: no-repeat url(../../../assets/img/trade/trade-5.jpg);
  background-size: cover;
}
.trade-bg-box .trade-bg.bg-6 {
  background: no-repeat url(../../../assets/img/trade/trade-6.jpg);
  background-size: cover;
}
.trade-bg-box .trade-bg .trade-info {
  width: 100%;
  height: 200px;
  background-image: radial-gradient(
    rgba(255, 255, 255, 0.95),
    rgba(255, 255, 255, 0.1)
  );
  text-align: center;
  padding-top: 70px;
  /* opacity: 0; */
}
.trade-bg-box .trade-bg .trade-info span {
  margin: 0 10px;
  font-size: 22px;
  color: #333;
}
/* .trade-bg-box .trade-bg:hover .trade-info {
  transition: opacity 0.3s linear;
  opacity: 1;
} */
</style>
