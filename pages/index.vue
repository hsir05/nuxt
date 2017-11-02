<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        nuxt template
      </h1>
      <div class="btn-wrop">
        <a href="/" class="btn btn1">首页</a>
        <a href="/about" class="btn btn2">about</a>
        <a href="/me" class="btn btn3">me</a>
        <a href="/users/news" class="btn btn3">users</a>
        <a href="/users/1" class="btn btn3">_id</a>
      </div>  
    </div>
  </section>
</template>
<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
