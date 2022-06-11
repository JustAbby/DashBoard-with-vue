<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <SideNav />
</template>

<script>
// @ is an alias to /src
import SideNav from '@/components/SideNavbar.vue'

export default {
  name: 'AboutView',
  components: {
    SideNav,
  }
}
</script>