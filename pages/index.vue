<template>
  <div>
    <section class="hero is-medium is-primary">
      <div class="hero-body">
        <div class="container">
          <p class="title">
            Large hero
          </p>
          <p class="subtitle">
            Large subtitle
          </p>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="columns is-mobile">
          <card
            title="Free"
            icon="github"
          >
            Open source on <a href="https://github.com/buefy/buefy">
              GitHub
            </a>
          </card>

          <card
            title="Responsive"
            icon="cellphone-link"
          >
            <b class="has-text-grey">
              Every
            </b> component is responsive
          </card>

          <card
            title="Modern"
            icon="alert-decagram"
          >
            Built with <a href="https://vuejs.org/">
              Vue.js
            </a> and <a href="http://bulma.io/">
              Bulma
            </a>
          </card>

          <card
            title="Lightweight"
            icon="arrange-bring-to-front"
          >
            No other internal dependency
          </card>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Card
  }
}
</script>
