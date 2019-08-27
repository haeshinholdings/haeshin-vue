<template>
  <div class="section">
    <div class="content">
      <figure class="iamge">
        <img src="~assets/img/index70_up.png" />
      </figure>
      <ApplicationOfAlibaba />
    </div>
  </div>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import ApplicationOfAlibaba from '~/components/main/ApplicationOfAlibaba'

export default {
  components: {
    AppLogo,
    ApplicationOfAlibaba
  },
  layout: 'default'
}
</script>