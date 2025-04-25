<template>
  <section class="contact-hero">
    <h1>Contact Us</h1>
  </section>
  <section class="contact-one">
    <img src="../assets/contactImages/img2.png" alt="img2" />
    <div class="contact-one-text">
      <h2>We'd love to talk about how we can work together.</h2>
      <p>
        Simply dummy text of the printing and typesetting industry. Lorem had
        ceased to been the industry's standard dummy text ever since the 1500s,
        when an unknown printer took a galley.
      </p>
      <div class="cards">
        <div>
          <img src="../assets/contactImages/img1.svg" alt="img1" />
          <div>
            <h6>Massege</h6>
            <p>support@organic.com</p>
          </div>
        </div>
        <div>
          <img src="../assets/contactImages/img2.svg" alt="img2" />
          <div>
            <h6>Massege</h6>
            <p>support@organic.com</p>
          </div>
        </div>
      </div>
      <div class="links">
        <img src="../assets/contactImages/1.svg" alt="img1" />
        <img src="../assets/contactImages/2.svg" alt="img2" />
        <img src="../assets/contactImages/3.svg" alt="img3" />
        <img src="../assets/contactImages/4.svg" alt="img4" />
      </div>
    </div>
  </section>
  <section class="conatct-two">
    <div>
      <div>
        <h6>Location</h6>
        <h3>Our Farms</h3>
        <p>
          Established fact that a reader will be distracted by the readable
          content of a page when looking a layout. The point of using.
        </p>
        <div>
          <img src="../assets/contactImages/icon.svg" alt="icon" />
          <p>
            <span>New York, USA:</span> 299 Park Avenue New York, New York 10171
          </p>
        </div>
        <div>
          <img src="../assets/contactImages/Icon.svg" alt="icon" />
          <p>
            <span>London, UK:</span>
            30 Stamford Street, London SE1 9LQ
          </p>
        </div>
      </div>
    </div>
  </section>
  <section class="email-form">
    <form>
      <label>
        Full Name* <br />
        <input type="text" placeholder="Your Email Address" />
      </label>
      <label>
        Your Email* <br />
        <input type="email" placeholder="example@yourmail.com" />
      </label>
      <label
        >Company* <br />
        <input type="text" placeholder="yourcompany name here" />
      </label>
      <label>
        Subject* <br /><input type="email" placeholder="how can we help" />
      </label>
      <label>
        Message* <br />
        <textarea
          placeholder="hello there,i would like to talk about how to..."
          cols="115%"
          rows="15px"
        ></textarea>
      </label>
      <button>Send Message</button>
    </form>
  </section>
</template>
<script>
export default {}
</script>
<style scoped>
/*hero*/
.contact-hero {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding: calc(184 / 19.2 * 1vw) 0px;
  background-image: url('../assets/contactImages/img1.png');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.contact-hero > h1 {
  font-family: Roboto, sans-serif;
  font-weight: 800;
  font-size: calc(60 / 19.2 * 1vw);
  line-height: 100%;
  color: #274c5b;
}
/*     contact-one      */
.contact-one {
  padding: calc(209 / 19.2 * 1vw) calc(260 / 19.2 * 1vw) calc(98 / 19.2 * 1vw);
  display: flex;
  align-items: center;
  column-gap: calc(60 / 19.2 * 1vw);
}
.contact-one > img {
  width: calc(624 / 19.2 * 1vw);
  height: calc(680 / 19.2 * 1vw);
  border-radius: calc(20 / 19.2 * 1vw);
}
.contact-one-text > h2 {
  font-family: Roboto, sans-serif;
  font-weight: 800;
  font-size: calc(45 / 19.2 * 1vw);
  line-height: 100%;
  color: #274c5b;
}
.contact-one-text > p {
  padding: calc(14 / 19.2 * 1vw) 0 calc(34 / 19.2 * 1vw);
  font-family: Open Sans, sans-serif;
  font-weight: 400;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 165%;
}
.cards {
  display: flex;
  flex-direction: column;
  row-gap: calc(17 / 19.2 * 1vw);
}
.cards > div {
  width: calc(352 / 19.2 * 1vw);
  padding: calc(11 / 19.2 * 1vw) calc(12 / 19.2 * 1vw);
  display: flex;
  align-items: center;
  column-gap: calc(19 / 19.2 * 1vw);
  border: calc(1 / 19.2 * 1vw) solid #eeeeee;
  border-radius: calc(11 / 19.2 * 1vw);
}
.cards > div > img {
  padding: calc(26 / 19.2 * 1vw) calc(22 / 19.2 * 1vw);
  width: calc(89 / 19.2 * 1vw);
  height: calc(89 / 19.2 * 1vw);
  border-radius: calc(11 / 19.2 * 1vw);
  background: #f4f4f4;
}
.cards > div > div > h6 {
  font-family: Roboto, sans-serif;
  font-weight: 800;
  font-size: calc(25 / 19.2 * 1vw);
  line-height: 100%;
  color: #274c5b;
}
.cards > div > div > p {
  font-family: Open Sans, sans-serif;
  font-weight: 400;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 165%;
  color: #525c60;
}

.links {
  padding-top: calc(34 / 19.2 * 1vw);
  display: flex;
  align-self: center;
  column-gap: calc(15 / 19.2 * 1vw);
}
.links {
  width: calc(100 / 19.2 * 1vw);
  height: calc(100 / 19.2 * 1vw);
}

/*      conatct-two       */
.conatct-two {
  padding: 0 calc(260 / 19.2 * 1vw) calc(80 / 19.2 * 1vw);
}
.conatct-two > div {
  padding: calc(122 / 19.2 * 1vw);
  border-radius: calc(20 / 19.2 * 1vw);
  width: 100%;
  height: auto;
  background-image: url('../assets/contactImages/Image.png');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-direction: column;
  align-items: end;
}
.conatct-two > div > div {
  border-radius: calc(30 / 19.2 * 1vw);
  background: #ffffff;
  padding: calc(46 / 19.2 * 1vw) calc(53 / 19.2 * 1vw);
  width: calc(514 / 19.2 * 1vw);
  height: 514;
}
.conatct-two > div > div > h6 {
  font-family: Yellowtail, sans-serif;
  font-weight: 400;
  font-size: calc(36 / 19.2 * 1vw);
  line-height: 100%;
  letter-spacing: 0%;
  color: #7eb693;
}
.conatct-two > div > div > h3 {
  padding: calc(5 / 19.2 * 1vw) 0 calc(10 / 19.2 * 1vw);
  font-family: Roboto, sans-serif;
  font-weight: 800;
  font-size: calc(50 / 19.2 * 1vw);
  line-height: 100%;
  color: #274c5b;
}
.conatct-two > div > div > p {
  font-family: Open Sans, sans-serif;
  font-weight: 400;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 165%;
  color: #525c60;
}
.conatct-two > div > div > div {
  padding-top: calc(20 / 19.2 * 1vw);
  display: flex;
  align-items: start;
  column-gap: calc(6 / 19.2 * 1vw);
}
.conatct-two > div > div > div > img {
  width: calc(50 / 19.2 * 1vw);
}
.conatct-two > div > div > div > p > span {
  color: #274c5b;
}
.conatct-two > div > div > div > p {
  width: calc(246 / 19.2 * 1vw);
  font-family: Open Sans;
  font-weight: 700;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 165%;
  color: #525c60;
}
/*       eamil-form          */
.email-form {
  padding: 0 calc(368 / 19.2 * 1vw);
}
.email-form > form {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: calc(46 / 19.2 * 1vw) calc(50 / 19.2 * 1vw);
}
.email-form > form > label {
  font-family: Roboto, sans-serif;
  font-weight: 600;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 100%;
  color: #274c5b;
}
.email-form > form > label > input {
  margin-top: calc(15 / 19.2 * 1vw);
  width: calc(539 / 19.2 * 1vw);
  height: auto;
  border-radius: calc(16 / 19.2 * 1vw);
  border: calc(1 / 19.2 * 1vw) solid #7eb693;
  padding: calc(28 / 19.2 * 1vw) calc(23 / 19.2 * 1vw);
  outline: none;
}
.email-form > form > label > input:placeholder {
  font-family: Roboto, sans-serif;
  font-weight: 400;
  font-style: italic;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 100%;
  color: #ababab;
}
.email-form > form > label > textarea {
  width: 100%;
  margin-top: calc(25 / 19.2 * 1vw);
  border-radius: calc(16 / 19.2 * 1vw);
  border: calc(1 / 19.2 * 1vw) solid #7eb693;
  outline: none;
  padding: calc(28 / 19.2 * 1vw) calc(23 / 19.2 * 1vw) 0;
}
.email-form > form > label > textarea:placeholder {
  font-family: Roboto, sans-serif;
  font-weight: 400;
  font-style: italic;
  font-size: calc(18 / 19.2 * 1vw);
  line-height: 100%;
  color: #ababab;
}
.email-form > form > button {
  padding: calc(28 / 19.2 * 1vw) calc(43 / 19.2 * 1vw);
  border-radius: calc(16 / 19.2 * 1vw);
  background: #274c5b;
  border: none;
  font-family: Roboto, sans-serif;
  font-weight: 700;
  font-size: calc(20 / 19.2 * 1vw);
  line-height: 100%;
  color: #ffffff;
}
</style>
