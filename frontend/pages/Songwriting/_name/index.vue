<template>
  <div class="container">
    <h1>My Life is My Worship</h1>
    <Info />
    <Video />
  </div>
</template>

<script>
import Info from '../../../components/Info'
import Video from '../../../components/Video'

export default {
  name: 'Song',
  components: {
    Info,
    Video,
  },
}
</script>
