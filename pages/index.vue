<template>
  <div class="container">
    <div class ="main">
      <logo />
      <h1 class="title">
        Asterisk
      </h1>
      <h2 class="subtitle">
        Hello, World!
      </h2>
      <div class ="message">
        <p>
          이 페이지는 서버 테스트 페이지입니다 :)
        </p>
        <p>
          This page is a server test page :)
        </p>
      </div>
    </div>
    <nuxt-footer />
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
    NuxtFooter: () => import('~/components/Footer.vue')
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.main {
  flex: 1;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #46C3FA;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #868E96;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.message {
  font-weight: 300;
  font-size: 16px;
  color: #ADB5BD;
  word-spacing: 2px;
  padding-bottom: 10px;
}
</style>
