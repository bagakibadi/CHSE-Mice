<template>
  <div class="contains">
    <div class="topnav">
      <div class="nav">
        <img src="https://i.ibb.co/VVnpYz0/miceshadow.png" >
      </div>
    </div>
    <div class="headers">
      <h1>Virtual Event CHSE Mice</h1>
      <p>Panduan Pelaksanaan Kebersihan, Keselamatan serta Kelestarian Lingkungan
       (Cleanliness, Health, Safety and Environmental sustainability/ CHSE) penyelenggaraan
       kegiatan Meeting, Incentive, Convention, Exhibition (MICE) yang diharapkan dapat menjadi
       acuan bagi Asosiasi, Industri dan seluruh stakeholders MICE dalam menyelenggarakan
        kegiatan MICE di era New Normal.</p>
    </div>
    <div class="wrap">
      <div class="cards">
        <h1>Yogyakarta</h1>
        <img src="../assets/icon/Yogyakarta.svg" style="margin-top:-45px">
        <div class="d-flex buton" style="margin-top: -30px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Yogyakarta"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Yogyakarta"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Surabaya</h1>
        <img src="../assets/icon/Surabaya.svg" style="margin-top:-18px">
        <div class="d-flex buton" style="margin-top: -58px;">
          <a href="https://mice.id/CHSEHBDIVING/offline/Surabaya"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Surabaya"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Medan</h1>
        <img src="../assets/icon/Medan.svg" >
        <div class="d-flex buton" style="margin-top: -75px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Medan"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Medan"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Bandung</h1>
        <img src="../assets/icon/Bandung.svg" style="margin-top:-15px">
        <div class="d-flex buton" style="margin-top: -60px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Bandung"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Bandung"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Manado</h1>
        <img src="../assets/icon/Manado.svg" >
        <div class="d-flex buton" style="margin-top: -75px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Manado"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Manado"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Lombok</h1>
        <img src="../assets/icon/Lombok.svg" style="margin-top:-15px">
        <div class="d-flex buton" style="margin-top: -60px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Lombok"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Lombok"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Batam</h1>
        <img src="../assets/icon/Batam.svg" >
        <div class="d-flex buton" style="margin-top: -60px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Batam"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Batam"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Semarang</h1>
        <img src="../assets/icon/Semarang.svg" >
        <div class="d-flex buton" style="margin-top: -60px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Semarang"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Semarang"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
      <div class="cards">
        <h1>Jakarta</h1>
        <img src="../assets/icon/Jakarta.svg" style="margin-top:-30px">
        <div class="d-flex buton" style="margin-top: -30px">
          <a href="https://mice.id/CHSEHBDIVING/offline/Jakarta"><div class="btn btn-primary">Offline</div></a>
          <a href="https://mice.id/CHSEHBDIVING/online/Jakarta"><div class="btn btn-primary">Online</div></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
  a{
    text-decoration: none;
    color: white;
  }
  .contains{
      width: 100%;
      height: auto;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 0 0 40px 0;
      background-image: url('https://i.ibb.co/rFWp2r1/Group-9.png');
      background-repeat: no-repeat;
      background-position-x: 13px;
      /* background-position-y: 20px; */
    }
    .headers{
      margin-top: 15px;
      width: 700px;
      height: auto;
      text-align: center;
    }
    .headers h1{
      font-weight: bold;
      margin-bottom: 10px;
      font-size: 28px;
    }
    .headers p{
      font-size: 14px;
    }
    .wrap{
      width: 100%;
      height: auto;
      padding: 0 120px 0 120px;
      display: flex;
      box-sizing: border-box;
      justify-content: space-around;
      flex-wrap: wrap;
    }
    .cards{
      border-radius: 20px;
      background: white;
      cursor: pointer;
      margin: 50px 30px 0px 30px;
      width: 300px;
      height: auto;
      text-align: center;
      overflow: hidden;
      box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.15);
      position: relative;
    }
    .cards h1{
      font-weight: normal;
      font-size: 25px;
      padding: 20px 0 0 0;
    }
    .buton {
      margin-top: -20px;
      width: 100%;
      justify-content: space-around;
      padding: 10px 0;
    }
    .buton .btn{
      width: 130px;
      border-radius: 100px;
    }
    /* .cards img{
      margin-top: -20px;
    } */
    .topnav{
      position: relative;
      width: 100%;
      height: 70px;
    }
    .nav{
      width: 100%;
      height: 70px;
      position: fixed;
      /* box-shadow: 0px 2px 10px 0px rgba(0,0,0,0.25);; */
      display: flex;
      align-items: center;
      background: transparent;
      z-index: 1;
    }
    .nav img{
      padding-left: 30px;
      width: 130px;
    }
    @media only screen and (max-width: 600px) {
      .contains {
        /* padding-left: 20px;
        padding-right: 20px; */
        box-sizing: border-box;
      }
      .cards{
        margin: 20px 0;
        width: 100%;
      }
      .headers{
        box-sizing: border-box;
        margin-bottom: 50px;
        width: 100%;
        padding: 0 20px;
      }
      .wrap{
        box-sizing: border-box;
        padding: 0 20px !important;
      }
    }
    @media only screen and (min-width: 1920px) {
      .cards{
        width: 300px;
        height: 300px;
      }
      .contains{
        background-position-x: right;
      }
    }
    @media only screen and (max-width: 992px) {
      .wrap{
        padding: 0 80px;
      }
      .cards{
        width: 280px;
      }
    }
</style>
