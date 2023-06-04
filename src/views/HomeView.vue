<template>
  <div class="home">
    <AppHeader />
    <section class="hero-section">
      <div class="text-and-image">
        <div class="text-content">
          <h1>Ласкаво просимо в нашу транспортну компанію</h1>
          <p>
            Ми - маленька, але амбітна транспортна компанія, спеціалізуємося на
            вантажних перевезеннях та встановленні меблів та техніки.
          </p>
        </div>
        <img src="../assets/logo.jpg" alt="Transport Image" />
      </div>
    </section>
    <section class="services-section">
      <div class="text-and-image">
        <div class="text-content">
          <h2>Наші послуги</h2>
          <p>
            Ми надаємо безпечну та надійну доставку вантажів уздовж маршрутів,
            що охоплюють широку територію, а також професійний демонтаж та
            монтаж кухонь, зменшення розмірів, підгон до ваших параметрів
            приміщення. Врізка техніки, мийки та інші роботи..
          </p>
        </div>
        <img src="../assets/services-image.jpg" alt="Services Image" />
      </div>
    </section>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "@/components/Header.vue";
import AppFooter from "@/components/Footer.vue";

export default {
  name: "HomeView",
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<style scoped>
.home {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  min-height: 100vh;
}

.hero-section,
.services-section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2em;
}

.text-and-image {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}

.text-content {
  width: 50%;
}

.text-and-image img {
  width: 40%;
  height: auto;
}

.text-and-image {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  width: 80%;
}

@media (max-width: 600px) {
  .text-and-image {
    flex-direction: column;
  }

  .text-content,
  .img {
    width: 80%;
  }
}
</style>
