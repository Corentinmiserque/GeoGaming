<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>

    <div class="wrapper">

      <nav class="test">
        <RouterLink to="/">Login</RouterLink>
        <RouterLink to="/home">Home</RouterLink>
        <RouterLink to="/rank">Rank</RouterLink>
        <RouterLink to="/profile">Profile</RouterLink>
        <RouterLink to="/game">Game</RouterLink>
        <RouterLink to="/nextgame">NextGame</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
