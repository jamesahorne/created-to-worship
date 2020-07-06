<template>
  <header class="header">
    <nuxt-link class="logo" to="/">Created to Worship</nuxt-link>
    <nav class="nav">
      <ul class="nav__list">
        <li class="nav__item">
          <nuxt-link class="nav__link" to="/songwriting">Songwriting</nuxt-link>
        </li>
        <li class="nav__item">
          <nuxt-link class="nav__link" to="/">Nav Item</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
}
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  padding: 2rem 0;
  max-width: 64rem;
  margin: 0 auto;
}

.nav__list {
  display: flex;
  justify-content: flex-end;
}

.nav__item {
  display: block;
  margin-right: 2rem;
}
.nav__item:last-child {
  margin-right: 0;
}
</style>
