<template>
  <Header />
  <div class='container'>
    <router-view />
  </div>
  <router-view/>
</template>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header,
  },
}
</script>

