<template>
  <header class="header">
    <div class="header-container">
      <div class="logo">
        <RouterLink to="/">
          <img src="../assets/headerImages/Logo.png" alt="Organick Logo">
          <span>Organick</span>
        </RouterLink>
      </div>
      
      <nav class="nav">
        <ul class="nav-list">
          <li class="nav-item"><RouterLink to="/">Home</RouterLink></li>
          <li class="nav-item"><RouterLink to="/about">About</RouterLink></li>
          <li class="nav-item"><RouterLink to="/shop">Shop</RouterLink></li>
          <li class="nav-item"><RouterLink to="/service">Service</RouterLink></li>
          <li class="nav-item"><RouterLink to="/contact">Contact</RouterLink></li>
        </ul>
      </nav>
      <div class="poisk">
        <input type="text">
        <img src="../assets/headerImages/Search Icon.png" alt="">
      </div>

      <div class="cart_icon">
        <img src="../assets/headerImages/Cart Icon.png" alt="">
        Cart (0)
      </div>
    </div>
  </header>
</template>

<script>
import { RouterLink } from "vue-router";
export default {};
</script>

<style scoped>
.header {
  padding: 20px 0;
  background: white;
  border-bottom: 1px solid #f5f5f5;
}

.header-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 40px;
}

.logo a {
  display: flex;
  align-items: center;
  gap: 10px;
  text-decoration: none;
}

.logo img {
  width: 36px;
  
}

.logo span {
  font-family: 'Roboto', sans-serif;
  font-size: 24px;
  font-weight: 700;
  color: #274C5B;
}

.nav-list {
  display: flex;
  gap: 40px;
  list-style: none;
  margin: 0;
  padding: 0;
}

.nav-item a {
  font-family: 'Roboto', sans-serif;
  font-size: 16px;
  font-weight: 600;
  color: #274C5B;
  text-decoration: none;
  transition: color 0.2s;
}

.nav-item a:hover {
  color: #7EB693;
}

.cart {
  font-family: 'Roboto', sans-serif;
  font-size: 16px;
  font-weight: 600;
  color: #274C5B;
  cursor: pointer;
}
.poisk {
  display: flex;
  justify-content: center;
  align-items: center;
  padding-left: calc(70 / 14.4 * 1vw);
}
.poisk img {
  position: relative;
  left: -45px;
  width: 46px;
}

.poisk input {
  width: 220px;
  height: 48px;
  border-radius: 25px;
  background: #FAFAFA;
  border: none;
outline: none;
}
.cart_icon {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  width: 130px;
  height: 46px;
  border-radius:22px ;
  border: 0.5px solid #E0E0E0;
}
.cart_icon img {
  width: 46px;
  position: relative;
  left: -10px;
}
@media (max-width: 768px) {
  .header-container {
    flex-direction: column;
    gap: 20px;
  }

  .nav-list {
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }

  .search-bar input {
    width: 100%;
  }
}

</style>