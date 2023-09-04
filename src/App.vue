<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>

    <div>
      <HelloWorld msg="You did it!" />

      <nav class="bg-slate-400 flex p-2 justify-end ps-8">
        <RouterLink to="/">
          <div>00</div>
          <div>HOME</div>
        </RouterLink>
        <RouterLink to="/about">
          <div>01</div>
          <div>DESTINATION</div>
        </RouterLink>
        <RouterLink to="/crew">
          <div>02</div>
          <div>CREW</div>
        </RouterLink>
        <RouterLink to="/technology">
          <div>03</div>
          <div>TECHNOLOGY</div>
        </RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

