<template>
  <!-- 1-Banner -->
  <section class="about-banner">
    <h1 id="robotoB">About Us</h1>
  </section>

  <!-- 2-Success -->
  <section class="about-success__wrapper">
    <div class="about-success__image">
      <img src="../assets/aboutImages/p-2.svg" alt="p-2" loading="lazy" width="850" />
    </div>
    <div class="about-success__info">
      <h3 class="yellowTail">About Us</h3>
      <h2 id="robotoB">We do Creative Things for Success</h2>
      <p>
        Simply dummy text of the printing and typesetting industry. Lorem had
        ceased to been the industry's standard dummy text ever since the 1500s,
        when an unknown printer took a galley.
      </p>
      <br />
      <p>
        Simply dummy text of the printing and typesetting industry. Lorem had
        ceased to been the industry's standard dummy text ever since the 1500s,
        when an unknown printer took a galley.
      </p>
      <div class="about-success__cards">
        <div class="about-success__card">
          <img src="../assets/aboutImages/p-3.svg" alt="p-3" loading="lazy" width="46" height="46" />
          <h5>Modern Agriculture Equipment</h5>
        </div>
        <div class="about-success__card">
          <img src="../assets/aboutImages/p-4.svg" alt="p-4" loading="lazy" width="46" height="46" />
          <h5>Modern Agriculture Equipment</h5>
        </div>
      </div>
      <a class="about-success__btn" href="#">Explore More <span>&rArr;</span></a>
      
    </div>
  </section>

  <!-- 3-Trade -->
   <section class="about-trade__wrapper">

    <div class="about-trade__info">
      <h3 class="yellowTail">Why choose us?</h3>
      <h2 id="robotoB">We do not buy from the
        open market & traders.</h2>
        <p>Simply dummy text of the printing and typesetting industry. Lorem had ceased to been the industry's standard  the 1500s, when an unknown</p>
        <div class="about-trade__statistics">
          <img src="../assets/aboutImages/p-5.svg" alt="p-5">
          <h4>100% Natural Product</h4>
        </div>
        <h6>Simply dummy text of the printing and typesetting industry Lorem Ipsum</h6>
        <div class="about-trade__statistics">
          <img src="../assets/aboutImages/p-5.svg" alt="p-5">
          <h4>Increases resistance</h4>
        </div>
        <h6>Filling, and temptingly healthy, our Biona Organic Granola with Wild Berries is just the thing</h6>
    </div>

    <div class="about-trade__image">
      <img src="../assets/aboutImages/p-6.svg" alt="p-6">
    </div>

    <div class="about-trade__cards">
      <div class="about-trade__card">
        <img src="../assets/aboutImages/p-7.svg" alt="p-7">
        <h6>Return Policy</h6>
        <p>Simply dummy text of the printintypesetting industry.</p>
      </div>
      <div class="about-trade__card">
        <img src="../assets/aboutImages/p-8.svg" alt="p-8">
        <h6>100% Fresh</h6>
        <p>Simply dummy text of the printintypesetting industry.</p>
      </div>
      <div class="about-trade__card">
        <img src="../assets/aboutImages/p-9.svg" alt="p-9">
        <h6>Support 24/7</h6>
        <p>Simply dummy text of the printintypesetting industry.</p>
      </div>
      <div class="about-trade__card">
        <img src="../assets/aboutImages/p-10.svg" alt="p-10">
        <h6>Secured Payment</h6>
        <p>Simply dummy text of the printintypesetting industry.</p>
      </div>
    </div>
  </section>
    <!-- 4-Experts -->
     <section class="about-experts__wrapper">
      <h3 class="yellowTail">Team</h3>
      <h2 id="robotoB">Our Organic Experts</h2>
      <p>Simply dummy text of the printing and typesetting industry. Lorem had ceased to been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley.</p>
      <div class="experts-cards">
        <div class="experts-card">
          <img src="../assets/aboutImages/p-11.svg" alt="p-11" loading="lazy" width="380">
          <div class="experts-card__info">
             <div class="experts-card__texts">
            <h4 id="robotoB">Giovani Bacardo</h4>
            <h5 class="yellowTail">Farmer</h5>
          </div>
          <div class="experts-card__links">
            <img src="../assets/aboutImages/p-14.svg" alt="p-14" loading="lazy" width="23">
            <img src="../assets/aboutImages/p-15.svg" alt="p-15" loading="lazy" width="23">
          </div>
          </div>
         
        </div>
        <div class="experts-card">
          <img src="../assets/aboutImages/p-12.svg" alt="p-12" loading="lazy" width="380">
          <div class="experts-card__info">
             <div class="experts-card__texts">
            <h4 id="robotoB">Marianne Loreno</h4>
            <h5 class="yellowTail">Designer</h5>
          </div>
          <div class="experts-card__links">
            <img src="../assets/aboutImages/p-16.svg" alt="p-16" loading="lazy" width="23">
            <img src="../assets/aboutImages/p-14.svg" alt="p-14" loading="lazy" width="23">
            <img src="../assets/aboutImages/p-15.svg" alt="p-15" loading="lazy" width="23">
          </div>
          </div>
         
        </div>
        <div class="experts-card">
          <img src="../assets/aboutImages/p-13.svg" alt="p-13" loading="lazy" width="380">
          <div class="experts-card__info">
             <div class="experts-card__texts">
            <h4 id="robotoB">Giovani Bacardo</h4>
            <h5 class="yellowTail">Farmer</h5>
          </div>
          <div class="experts-card__links">
            <img src="../assets/aboutImages/p-16.svg" alt="p-16" loading="lazy" width="23">
            <img src="../assets/aboutImages/p-14.svg" alt="p-14" loading="lazy" width="23">
            <img src="../assets/aboutImages/p-15.svg" alt="p-15" loading="lazy" width="23">
          </div>
          </div>
         
        </div>
      </div>
    </section>

    <!-- 5-Offer -->
   <section class="about-offer__wrapper">
    <h3 class="yellowTail">About Us</h3>
    <h2 id="robotoB">What We Offer for You</h2>
    <IbrohimsSwiper/>
   </section>
</template>
<script>
import IbrohimsSwiper from '@/components/ibrohimsSwiper/IbrohimsSwiper.vue';
export default {
  components: {
    IbrohimsSwiper
  }
}
</script>
<style>
/* Font-Roboto */
@font-face {
  font-family: 'RobotoB';
  src: url('../assets/IFonts/roboto/static/Roboto-ExtraBold.ttf')
    format('truetype');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'Roboto';
  src: url('../assets/IFonts/roboto/static/Roboto-Regular.ttf')
    format('truetype');
  font-weight: normal;
  font-style: normal;
}
/* Font-YellowTail */
@font-face {
  font-family: 'YellowTail';
  src: url('@/assets/IFonts/yellowTail/Yellowtail-Regular.ttf');
  font-weight: normal;
  font-style: normal;
}
body {
  font-family: 'Roboto', sans-serif;
}
#robotoB {
  font-family: 'RobotoB', sans-serif;
}
.yellowTail {
  font-family: 'YellowTail', sans-serif;
  color: rgba(126, 182, 147, 1);
  font-size: calc(38 / 19.2 * 1vw);
  line-height: 1.5;
}

/* 1-About-banner */
.about-banner {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 400px;
  background-image: url('../assets/aboutImages/p-1.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
}
.about-banner h1 {
  font-size: calc(68/19.2 * 1vw);
  color: rgba(39, 76, 91, 1);
  letter-spacing: -1px;
}
 /* 2-About-success */
.about-success__wrapper {
  gap: 30px;
  display: grid;
  grid-template-columns: repeat(2,1fr);
  align-items: center;
  justify-content: center;
}
.about-success__image img {
  width: calc(1000/19.2 *1vw);
  padding-top: 163px;
}
.about-success__info h2{
  width: 400px;
  color: rgba(39, 76, 91, 1);
  margin-bottom: 14px;
  font-size: calc(50/19.2 *1vw);
}
.about-success__info p {
  font-weight: 400;
  font-size: calc(18/19.2 *1vw);
  color: rgba(82, 92, 96, 1);
}
.about-success__cards {
  display: flex;
  gap: 65px;
  align-items: center;
  justify-content: flex-start;
  margin: 48px 0;
}
.about-success__card {
  width: 250px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 15px;
}
.about-success__card img {
  width: calc(55/19.2 *1vw);
}
.about-success__card h5 {
  font-weight: 600;
  font-size: calc(25/19.2 *1vw);
  line-height: 1.2;
  color: rgba(39, 76, 91, 1);
}
.about-success__btn {
  transition: all 500ms ease;
  display: inline-block;
  font-size: calc(20/19.2 *1vw);
  padding: 22px 35px;
  background-color: rgba(39, 76, 91, 1);
  border-radius: 16px;
  font-weight: 700;
  color: rgba(255, 255, 255, 1);
}
.about-success__btn:hover {
  background-color: rgba(51, 91, 107, 1);
}
.about-success__btn span {
  margin-left: 10px;
  padding: 5px 6px;
  background-color: rgba(51, 91, 107, 1);
  border-radius: 50%;
}

/* 3-Trade */
.about-trade__wrapper {
  width: 100%;
  height: 1429px;
  display: grid;
  grid-template-columns: repeat(2,1fr);
  background-color: rgba(249, 248, 248, 1);
  padding: 0 100px ;
}
.about-trade__info {
  align-self: center;
  justify-self: center;
  width: 671px;
  height: 624px;
}
.about-trade__info h2 {
  width: 504px;
  font-size: calc(50/19.2 *1vw);
  line-height: 1.2;
  color: rgba(39, 76, 91, 1);
  margin-bottom: 25px;
}
.about-trade__info p {
  font-weight: normal;
  font-size: calc(18/19.2 *1vw);
  line-height: 1.5;
  color: rgba(82, 92, 96, 1);
  margin-bottom: 36px;
}
.about-trade__statistics {
  width: 339px;
  height: 81px;
  background-color: rgba(236, 236, 236, 1);
  border-radius: 49px;
  display: flex;
  gap: 7px;
  align-items: center;
  justify-content: flex-start;
  padding-left: 27px;
  margin-bottom: 12px;
}
.about-trade__statistics img {
  width: calc(22/19.2 *1vw);
}
.about-trade__info h6 {
  width: 400px;
  font-size: calc(18/19.2 *1vw);
  line-height: 1.2;
  color: rgba(82, 92, 96, 1);
  padding-left: 60px;
  margin-bottom: 24px;
  font-weight: normal;
}
.about-trade__cards {
  width: 1118px;
  grid-column: 1 /-1;
  display: flex;
  align-self: center;
  justify-self: center;
  gap: 30px;
  align-items: center;
  justify-content: center;
  flex-basis: 257px;
  flex-grow: 1;
}

.about-trade__card {
  transition: all 500ms ease;
  min-width: 257px;
  text-align: center;
  display: flex;
  gap: 15px;
  height: 335px;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  border-radius: 30px;
  background-color: rgba(255, 255, 255, 1);
}
.about-trade__card:hover {
  transform: scale(1.1);
  cursor: pointer;
  background-color: rgba(148, 148, 148, 0.463);
}
.about-trade__card img {
  width: calc(110/19.2 *1vw);
}
.about-trade__card h6 {
  font-size: calc(25/19.2 *1vw);
  color: rgba(39, 76, 91, 1);
}
.about-trade__card p {
  width: 160px;
  font-size: calc(18/19.2 *1vw);
  color: rgba(82, 92, 96, 1);
}
.about-trade__image {
  align-self: center;
  justify-self: center;
}
.about-trade__image img {
  border-radius: 22px;
}

/* 4-Experts */
.about-experts__wrapper {
  width: 100%;
  height: 1000px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.about-experts__wrapper h2 {
  font-size: calc(50/19.2 *1vw);
  color: rgba(39, 76, 91, 1);
  line-height: 1.2;
  margin-bottom: 16px;
}
.about-experts__wrapper p {
  text-align: center;
  width: 720px;
  font-size: calc(19/19.2 *1vw);
  color: rgba(82, 92, 96, 1);
  line-height: 1.5;
  margin-bottom: 42px;
}
.experts-cards {
  display: flex;
  gap: 27px;
  align-items: center;
  justify-content: center;
}
.experts-card {
  background-color: rgba(249, 248, 248, 1);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  position: relative;
  overflow: hidden;
  width: 380px;
  height: 550px;
  border-radius: 30px;
}
.experts-card img {
  transition: all 500ms ease;
  margin-bottom: 35px;
}
.experts-card img:hover {
  transform: scale(1.1);
}
.experts-card__info {
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  padding: 0 28px;
}
.experts-card__texts {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
.experts-card__texts h5 {
  font-size: calc(24/19.2 *1vw);
}
.experts-card__texts h4 {
  font-size: calc(26/19.2 *1vw);
  color: rgba(39, 76, 91, 1);
}
.experts-card__links {
  display: flex;
  height: 100%;
  gap: 17px;
  align-items: flex-end;
  justify-content: center;
  padding-top: 30px;
}

/* 5-Offer */
.about-offer__wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 892px;
  background-color: rgba(39, 76, 91, 1);
}
.about-offer__wrapper h2 {
  font-size: calc(50/19.2 *1vw);
  color: rgba(255, 255, 255, 1);
}
</style>
