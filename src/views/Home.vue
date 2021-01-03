<template>
  <div class="home">
   <FatherComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import FatherComponent from '@/components/FatherComponent.vue'

export default {
  name: 'Home',
  components: {
    FatherComponent
  }
}
</script>
