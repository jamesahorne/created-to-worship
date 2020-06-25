<template>
  <div class="container">
    <h1>Songwriting</h1>
    <Info />
    <ul class="videos">
      <li>
        <Video />
      </li>
      <li>
        <Video />
      </li>
      <li>
        <Video />
      </li>
      <li>
        <Video />
      </li>
    </ul>
  </div>
</template>

<script>
import Info from '../../components/Info'
import Video from '../../components/Video'

export default {
  name: 'Songwriting',
  components: {
    Info,
    Video,
  },
}
</script>

<style scoped>
.videos {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
}
</style>
