<template>
  <section class="section">
      <div class="container">
            <nav class="level">
                <b-message v-if="error.statusCode === 404" closable="true" type="is-danger" has-icon>Page not found</b-message>
                <div class="level-item">
                    <button class="button block" type="is-link" ><nuxt-link to="/">home page</nuxt-link></button>
                </div>
            </nav>
      </div>
  </section>
</template>

<script>
export default {
  props: ['error'],
  layout: 'default'
}
</script>