<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-brand">
          <a class="navbar-item" href="/">
            Organic Tech Acceleration Platform
          </a>

          <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
            <span aria-hidden="true" />
            <span aria-hidden="true" />
            <span aria-hidden="true" />
          </a>
        </div>

        <div class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link
              v-for="(item, key) of items"
              :key="key"
              :to="item.to"
              class="navbar-item"
              exact-active-class="is-active"
            >
              {{ item.title }}
            </nuxt-link>

            <div class="navbar-item">
              <div class="buttons">
                <a class="button is-primary">
                  <strong>Apply</strong>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <nuxt />
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          title: 'About',
          to: { name: 'index' }
        },
        {
          title: 'Ignite',
          to: { name: 'ignite' }
        }
      ]
    }
  }
}
</script>
