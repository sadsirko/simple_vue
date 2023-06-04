<template>
  <div class="contact">
    <AppHeader />
    <h1>📞 Наші контакти</h1>
    <div class="contact-info">
      <p>
        📱 Телефон(Олександр): <a href="tel:+4901791447312">+4901791447312</a>
      </p>
      <p>
        📨 Електронна пошта:
        <a href="mailto:info@transport.com">info@transport.com</a>
      </p>
      <p>
        📬 Telegram: <a href="tg://resolve?domain=AdvUkrainen">@AdvUkrainen</a>
      </p>
      <p>
        📳 Viber:
        <a href="viber://chat?number=+4901791447312">+4901791447312</a>
      </p>
      <p>
        ☎️ WhatsApp: <a href="https://wa.me/4901791447312">+4901791447312</a>
      </p>
      <p>
        📬 Канал об'яв Telegram (звертайтеся в особисті):
        <a href="tg://resolve?domain=AdvUkrainen">@AdvUkrainen</a>
      </p>
    </div>
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "@/components/Header.vue";
import AppFooter from "@/components/Footer.vue";

export default {
  name: "ContactView",
  components: {
    AppHeader,
    AppFooter,
  },
};
</script>

<style scoped>
/* Styles for your contact page */
.contact {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  min-height: 10vh;
}

.contact-info {
  background-color: #f5f5f5;
  padding: 1rem;
  border-radius: 5px;
  font-size: 2rem;
}

footer {
  bottom: 0;
  width: 100%;
  border-top: 1px solid #ddd;
}
</style>
