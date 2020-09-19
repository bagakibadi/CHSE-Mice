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
          <div @click="offYogyakarta" class="btn btn-primary">Offline</div>
          <div @click="onYogyakarta" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Bandung</h1>
        <img src="../assets/icon/Bandung.svg" style="margin-top:-15px">
        <div class="d-flex buton" style="margin-top: -60px">
          <div @click="offBandung" class="btn btn-primary">Offline</div>
          <div @click="onBandung" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Medan</h1>
        <img src="../assets/icon/Medan.svg" >
        <div class="d-flex buton" style="margin-top: -75px">
          <div @click="offMedan" class="btn btn-primary">Offline</div>
          <div @click="onMedan" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Surabaya</h1>
        <img src="../assets/icon/Surabaya.svg" style="margin-top:-18px">
        <div class="d-flex buton" style="margin-top: -58px;">
          <div @click="offSurabaya" class="btn btn-primary">Offline</div>
          <div @click="onSurabaya" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Manado</h1>
        <img src="../assets/icon/Manado.svg" >
        <div class="d-flex buton" style="margin-top: -75px">
          <div @click="offManado" class="btn btn-primary">Offline</div>
          <div @click="onManado" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Lombok</h1>
        <img src="../assets/icon/Lombok.svg" style="margin-top:-15px">
        <div class="d-flex buton" style="margin-top: -60px">
          <div @click="offLombok" class="btn btn-primary">Offline</div>
          <div @click="onLombok" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Batam</h1>
        <img src="../assets/icon/Batam.svg" >
        <div class="d-flex buton" style="margin-top: -60px">
          <div @click="offBatam" class="btn btn-primary">Offline</div>
          <div @click="onBatam" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Semarang</h1>
        <img src="../assets/icon/Semarang.svg" >
        <div class="d-flex buton" style="margin-top: -60px">
          <div @click="offSemarang" class="btn btn-primary">Offline</div>
          <div @click="onSemarang" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
      <div class="cards">
        <h1>Jakarta</h1>
        <img src="../assets/icon/Jakarta.svg" style="margin-top:-30px">
        <div class="d-flex buton" style="margin-top: -30px">
          <div @click="offJakarta" class="btn btn-primary">Offline</div>
          <div @click="onJakarta" class="btn btn-primary"
          style="background: #FFCD1E;border:1px solid #ffcd1e">Online</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Swal from 'sweetalert2';

export default {
  methods: {
    offYogyakarta() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Yogyakarta';
        }
      });
    },
    onYogyakarta() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Yogyakarta';
        }
      });
    },
    offBandung() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Bandung';
        }
      });
    },
    onBandung() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Bandung';
        }
      });
    },
    offMedan() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Medan';
        }
      });
    },
    onMedan() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Medan';
        }
      });
    },
    offSurabaya() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Surabaya';
        }
      });
    },
    onSurabaya() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Surabaya';
        }
      });
    },
    offManado() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Manado';
        }
      });
    },
    onManado() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Manado';
        }
      });
    },
    offLombok() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Lombok';
        }
      });
    },
    onLombok() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Lombok';
        }
      });
    },
    offBatam() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Batam';
        }
      });
    },
    onBatam() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Batam';
        }
      });
    },
    offSemarang() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Semarang';
        }
      });
    },
    onSemarang() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Semarang';
        }
      });
    },
    offJakarta() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara offline?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/offline/Jakarta';
        }
      });
    },
    onJakarta() {
      Swal.fire({
        text: ' ',
        title: 'Apakah bapak/ibu akan menghadiri meeting secara online?',
        // icon: 'warning',
        showCancelButton: true,
        confirmButtonColor: '#3085d6',
        cancelButtonColor: '#d33',
        confirmButtonText: 'Ya',
        cancelButtonText: 'Tidak',
      }).then((result) => {
        if (result.isConfirmed) {
          window.location.href = 'https://mice.id/CHSEHBDIVING/online/Jakarta';
        }
      });
    },
  },
};
</script>

<style scoped>
  @font-face {
    font-family: 'Magistoe';
    src: url('../assets/font/magistoe/Magistoe.ttf');
  }
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
      background-image: url('https://i.ibb.co/L0Tsm7R/background-05-3-150x-1.png');
      background-repeat: no-repeat;
      background-size: cover;
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
      font-size: 45px;
      padding: 20px 0 0 0;
      font-family: 'Magistoe';
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
    .topnav{
      position: relative;
      width: 100%;
      height: 70px;
    }
    .nav{
      width: 100%;
      height: 70px;
      position: fixed;
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
        background: url('https://i.ibb.co/yBBSb67/background-mobile-bott-150x.png') bottom, url('https://i.ibb.co/hYfbhMT/background-mobile-up-150x.png') top;
        box-sizing: border-box;
        background-size: contain;
        background-repeat: no-repeat;
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
        height: auto;
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
