<template>
  <div class="AppFooter">
    <p class="text">Proudly Created with <a href="https://vuejs.org/" target="_blank">Vue</a>, and Powered by <a href="https://github.com/vuex-orm/vuex-orm">Vuex ORM</a>.</p>
  </div>
</template>

<style scoped>
@import "@/assets/styles/variables";

.AppFooter {
  padding-top: 96px;
  text-align: center;
  color: var(--c-gray);

  a {
    color: var(--c-black);
    transition: all .3s;
  }

  a:hover {
    color: var(--c-gray);
  }
}
</style>
