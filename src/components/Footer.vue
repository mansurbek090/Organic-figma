<template>
  <footer>
    <div class="top-foter">
      <img src="../assets/footerImages/Background (1).png" alt="img2" />
      <div class="top-fot-lorem">
        <h1>Subscribe to our Newsletter</h1>
        <div class="top-fot-btn">
          <input type="text" placeholder="Your Email Address" />
          <button>Subscribe</button>
        </div>
      </div>
    </div>
    <div class="footer-bot">
      <div class="fot-cantact">
        <h2>Contact Us</h2>
        <p>
          <span>Email </span> <br />needhelp@Organia.com <br /><br />
          <span>Phone </span> <br />666 888 888 <br /><br /><span>
            Address <br
          /></span>
          88 road, borklyn street, USA
        </p>
      </div>
      <div class="fot-center">
        <div class="fot-center-title">
          <img src="../assets/headerImages/Logo.png" alt="logos" />
          <h1>Organick</h1>
        </div>
        <p>
          Simply dummy text of the printing and typesetting industry. Lorem
          Ipsum simply dummy text of the printing
        </p>
        <img src="../assets/footerImages/Follow.png" alt="follow" />
      </div>
      <div class="fot-right">
        <h1>Utility Pages</h1>
        <p>
          Style Guide <br />
          <span>404 Not Found</span> <br />
          Password Protected <br />
          <span> Licences</span> <br />
          Changelog
        </p>
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style scoped>
.fot-right p {
  padding-top: 32px;
  width: 280px;
  height: 240px;

  font-family: Open Sans;
  font-weight: 400;
  font-size: 18px;
  line-height: 50px;
  letter-spacing: 0%;
}

.fot-center-title {
  padding-left: 120px;
}
.fot-center-title h1 {
  font-family: Roboto;
  font-weight: 700;
  font-size: 38px;
  line-height: 100%;
  color: rgba(39, 76, 91, 1);
  padding-left: 9px;
  padding-top: 8px;

  letter-spacing: 0%;
}
.fot-cantact {
  text-align: right;
}
.fot-cantact h1 {
  font-family: Roboto;
  font-weight: 700;
  font-size: 30px;
  line-height: 100%;
  letter-spacing: 0%;
  color: rgba(39, 76, 91, 1);
  padding-bottom: 32px;
}
.fot-cantact p {
  padding-top: 32px;
  width: 280px;
  height: 240px;

  font-family: Open Sans;
  font-weight: 400;
  font-size: 18px;
  line-height: 165%;
  letter-spacing: 0%;
}
.fot-cantact p span {
  font-family: Open Sans;
  font-weight: 500;
  padding-bottom: 12px;
  font-size: 19px;
  line-height: 165%;
  letter-spacing: 0%;
  text-align: right;
}
.fot-center p {
  font-family: Open Sans;
  font-weight: 400;
  font-size: 18px;
  line-height: 165%;
  letter-spacing: 0%;
  color: rgba(82, 92, 96, 1);
  padding-top: 25px;
  padding-bottom: 50px;
  width: 490px;
}

.fot-center-title {
  display: flex;
}
.fot-center {
  text-align: center;
}
.fot-center img:nth-child(1) {
  width: 36px;
  height: 53px;
}
.footer-bot {
  display: flex;
  width: 100%;
  justify-content: center;
  height: 500px;

  gap: 93px;
}
.top-fot-btn button {
  width: 220px;
  height: 80px;
  background: rgba(39, 76, 91, 1);
  border-radius: 18px;
  font-family: Roboto;
  font-weight: 700;
  border: 1px solid rgba(39, 76, 91, 1);
  font-size: 20px;
  line-height: 100%;
  letter-spacing: 0%;
  color: rgba(255, 255, 255, 1);
  transition: 0.3s ease;
}
.top-fot-btn {
  padding-top: 20px;
}
.top-fot-btn button:hover {
  background: rgba(255, 255, 255, 1);
  border: 1.8px solid rgba(39, 76, 91, 1);
  color: rgba(39, 76, 91, 1);
}
.top-fot-btn input {
  width: 350px;
  height: 80px;
  background: rgba(255, 255, 255, 1);
  font-family: Roboto;
  font-weight: 400;
  border: 1px solid rgba(255, 255, 255, 1);
  font-style: italic;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 0%;
  color: rgba(171, 171, 171, 1);
  padding-left: 20px;
  margin-right: 7px;
  border-radius: 18px;
}

.top-foter {
  width: 100%;
  height: 325px;
  position: relative;
  padding-top: 140px;
  margin-bottom: 270px;
}

.top-foter img {
  width: 100%;
  height: 325px;
}

.top-fot-lorem {
  position: absolute;
  top: 77%;
  left: 10%;
  text-align: center;
  gap: 330px;
  display: flex;
}
.top-fot-lorem h1 {
  font-family: Roboto;
  text-align: left;
  font-weight: 800;
  font-size: 50px;
  line-height: 100%;
  letter-spacing: 0%;
  color: rgba(255, 255, 255, 1);
  width: 357px;
}
</style>
