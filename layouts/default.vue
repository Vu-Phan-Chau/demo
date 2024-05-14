<template>
  <div>
    <HeaderComponent />
    <slot />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from '~/components/header/index.vue'
import FooterComponent from '~/components/footer/index.vue'

export default {
  components: { HeaderComponent, FooterComponent },
}
</script>
