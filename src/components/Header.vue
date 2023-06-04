<template>
  <header class="header">
    <nav class="nav">
      <router-link class="nav-link" to="/">
        <img
          class="logo"
          width="64"
          height="64"
          alt="Our logo"
          src="../assets/logo-modified.png"
        />
      </router-link>
      <router-link class="nav-link" to="/">Головна</router-link>
      <router-link class="nav-link" to="/about">Про нас</router-link>
      <router-link class="nav-link" to="/contact">Контакти</router-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 30px;
  background-color: #f5f5f5;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
  width: 100%;
  box-sizing: border-box;
}

.nav {
  display: flex;
  align-items: center;
  width: 100%;
  justify-content: space-between;
}

.logo {
  margin-right: 15px;
}

.nav-link {
  margin: 0 10px;
  text-decoration: none;
  color: #333;
}

.language-select {
  margin-left: 15px;
}
</style>
