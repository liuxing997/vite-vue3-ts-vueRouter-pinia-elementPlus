<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
    <a href="https://pinia.web3doc.top/" target="_blank">
      <img src="/pinia.svg" class="logo pinia" alt="pinia logo" />
    </a>
    <a href="https://element-plus.gitee.io/zh-CN/" target="_blank">
      <img
        src="/element-plus.svg"
        class="logo element-plus"
        alt="element-plus logo"
      />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue + pinia + Element-Plus." />
</template>

<script setup lang="ts">
import HelloWorld from "../components/HelloWorld.vue";
</script>

<style lang="less">
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.logo.pinia:hover {
  filter: drop-shadow(0 0 2em #150decaa);
}

.logo.element-plus:hover {
  filter: drop-shadow(0 0 2em #b87142aa);
}
</style>
