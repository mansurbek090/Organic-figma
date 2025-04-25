
<template>
  <div class="services">
    <!-- Hero Section -->
    <section class="hero">
    </section>

    <section class="showcase">
      <div class="content">
        <p class="subtitle">What we Grow</p>
        <h2 class="title">Better Agriculture for <br />Better Future</h2>

        <div class="grid">
          <!-- Left services -->
          <div class="features">
            <div v-for="(item, index) in leftServices" :key="index" class="feature-item">
              <img :src="item.icon" alt="icon" />
              <div>
                <h4>{{ item.title }}</h4>
                <p>{{ item.text }}</p>
              </div>
            </div>
          </div>

          <!-- Center image -->
          <div class="image-wrapper">
            <img src="../assets/servicesimg/Image (2).png" alt="product bag" />
          </div>

          <!-- Right services -->
          <div class="features">
            <div v-for="(item, index) in rightServices" :key="index" class="feature-item">
              <img :src="item.icon" alt="icon" />
              <div>
                <h4>{{ item.title }}</h4>
                <p>{{ item.text }}</p>
              </div>
            </div>
          </div>
        </div>

        <button class="explore-btn">Explore More</button>
      </div>
    </section>

    <!-- Video Section -->
    <section class="video">
      <p class="video-subtitle">Organic Only</p>
      <h2 class="video-title">Everyday Fresh & Clean</h2>
      <p class="video-text">
        Simply dummy text of the printing and typesetting industry. Lorem had ceased to be the industry's
        standard dummy text ever since the...
      </p>
      <div class="video-btn-container">
        <button class="play-btn">▶️</button>
      </div>
    </section>


  </div>
</template>

<script>
export default {};
const leftServices = [
  { icon: '/icons/dairy.svg', title: 'Dairy Products', text: 'Sed ut perspiciatis unde omnis iste natus error...' },
  { icon: '/icons/store.svg', title: 'Store Services', text: 'Sed ut perspiciatis unde omnis iste natus error...' },
  { icon: '/icons/delivery.svg', title: 'Delivery Services', text: 'Sed ut perspiciatis unde omnis iste natus error...' },
]

const rightServices = [
  { icon: '/icons/agriculture.svg', title: 'Agricultural Services', text: 'Sed ut perspiciatis unde omnis iste natus error...' },
  { icon: '/icons/organic.svg', title: 'Organic Products', text: 'Sed ut perspiciatis unde omnis iste natus error...' },
  { icon: '/icons/vegetables.svg', title: 'Fresh Vegetables', text: 'Sed ut perspiciatis unde omnis iste natus error...' },
]
</script>

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css');

.services {
  font-family: sans-serif;
  color: #274C5B;
}

/* Hero */
.hero {
  background-image: url('../assets/servicesimg/Banner.jpg');
  background-size: cover;
  background-position: center;
  height: 250px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero-title {
  color: white;
  font-size: 2rem;
  font-weight: bold;
  text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
}

.showcase {
  padding: 4rem 1rem;
  text-align: center;
}

.content {
  max-width: 1200px;
  margin: 0 auto;
}

.subtitle {
  color: #5b9f63;
  font-weight: 500;
  font-style: italic;
  margin-bottom: 0.5rem;
}

.title {
  font-size: 2rem;
  font-weight: bold;
  margin-bottom: 3rem;
}

.grid {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 2rem;
  flex-wrap: wrap;
}

.features {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  flex: 1;
}

.feature-item {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  text-align: left;
}

.feature-item img {
  width: 30px;
  height: 30px;
}

.image-wrapper {
  flex: 1;
  text-align: center;
}

.image-wrapper img {
  width: 100%;
  max-width: 300px;
  border-radius: 10px;
}


.explore-btn {
  margin-top: 3rem;
  padding: 0.75rem 1.5rem;
  border: 2px solid #0b2c3d;
  background-color: transparent;
  color: #0b2c3d;
  border-radius: 30px;
  font-weight: 500;
  cursor: pointer;
}

.explore-btn:hover {
  background-color: #0b2c3d;
  color: #fff;
}

/* Video */
.video {
  width: 100%;
  height: 650px;
  background-image: url('../assets/servicesimg/baaa.png');
  background-size: cover;
  background-position: center;
  padding: 80px 20px;
  text-align: center;
}

.video-subtitle {
  color: #7EB693;
  font-style: italic;
}

.video-title {
  font-size: 28px;
  font-weight: bold;
  margin: 10px 0;
}

.video-text {
  max-width: 600px;
  margin: 0 auto;
  color: #666;
}

.video-btn-container {
  margin-top: 20px;
}

.play-btn {
  width: 56px;
  height: 56px;
  background: #274C5B;
  color: white;
  font-size: 20px;
  border-radius: 50%;
  border: none;
  cursor: pointer;
  transition: transform 0.3s;
}

.play-btn:hover {
  transform: scale(1.1);
}

/* Footer */
.footer {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  justify-content: space-between;
  padding: 60px 20px;
  background: white;
  color: #274C5B;
}

.footer-title {
  font-weight: 600;
  margin-bottom: 8px;
}

.logo-title {
  font-size: 24px;
  font-weight: bold;
}

.socials {
  display: flex;
  justify-content: center;
  gap: 16px;
  font-size: 20px;
  margin-top: 10px;
}

.utility-list {
  list-style: none;
  padding: 0;
}

.utility-list li {
  color: #666;
  margin-bottom: 6px;
}

.bottom-footer {
  text-align: center;
  font-size: 14px;
  color: #888;
  border-top: 1px solid #ccc;
  padding: 20px;
}

/* Responsive */
@media (max-width: 768px) {
  .features {
    flex-direction: column;
  }

  .footer {
    flex-direction: column;
    text-align: center;
  }

  .features-left,
  .features-right {
    text-align: center;
  }
}
</style>