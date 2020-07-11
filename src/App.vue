<template>
  <div>
    <ObsidianNavbar />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ObsidianNavbar from './navbars/obsidian/ObsidianNavbar.vue'

export default {
  name: 'App',
  components: {
      HelloWorld,
      ObsidianNavbar
  }
}
</script>
