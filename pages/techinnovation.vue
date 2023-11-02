<template>
  <section class="posts">
    <div class="container">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <div class="columns featured-post is-multiline">
            <div class="column is-12 post">
              <article class="columns featured">
                <div
                  class="column is-10 is-offset-1 featured-content va has-text-centered"
                >
                  <p>
                    31 October – 2 November 2023 Sands Expo and Convention
                    Centre, Marina Bay Sands, Singapore Focusing on the primary
                    theme of Sustainable Urban Living, Health and Well-being,
                    TechInnovation 2023 will feature a unique blend of
                    content-rich conferences, exhibitions and business
                    networking over three days
                  </p>
                  <br>
                  <h1 class="title post-title">5 Creative Products</h1>
                  <p class="post-excerpt">
                    Under the project “Organic Tech Accelerator Platform.
                  </p>
                </div>
              </article>
            </div>
          </div>
          <hr />
          <div class="columns is-multiline">
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 featured-content">
                  <h1 class="title post-title">1. DroneBox (GIS)</h1>
                  <div class="column is-12 post-img">
                    <img src="~/assets/alliance/1.png" alt="Featured Image" />
                  </div>
                  <br />
                  <a
                    href="https://www.facebook.com/mapedia.co.th"
                    target="_blank"
                  >
                    <b-button label="Website" type="is-primary" />
                  </a>
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 featured-content">
                  <h1 class="title post-title">2. Smart Stain (MEDTECH)</h1>
                  <div class="column is-12 post-img">
                    <img src="~/assets/alliance/2.png" alt="Featured Image" />
                  </div>
                  <br />
                  <a
                    href="https://www.facebook.com/profile.php?id=61550342373607"
                    target="_blank"
                  >
                    <b-button label="Website" type="is-primary" />
                  </a>
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 featured-content">
                  <h1 class="title post-title">3. Better White (FOODTECH)</h1>
                  <div class="column is-12 post-img">
                    <img src="~/assets/alliance/3.png" alt="Featured Image" />
                  </div>
                  <br />
                  <a
                    href="https://web.facebook.com/NutriInnoFood/?_rdc=1&_rdrL"
                    target="_blank"
                  >
                    <b-button label="Website" type="is-primary" />
                  </a>
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 featured-content">
                  <h1 class="title post-title">4.Phytotant (ENVIRONMENT)</h1>
                  <div class="column is-12 post-img">
                    <img src="~/assets/alliance/4.png" alt="Featured Image" />
                  </div>
                  <br />
                  <a
                    href="https://web.facebook.com/Phytohemp.official?_rdc=1&_rdr"
                    target="_blank"
                  >
                    <b-button label="Website" type="is-primary" />
                  </a>
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 featured-content">
                  <h1 class="title post-title">
                    5.Quantum Biotech (ENVIRONMENT)
                  </h1>
                  <div class="column is-12 post-img">
                    <img src="~/assets/alliance/5.png" alt="Featured Image" />
                  </div>
                  <br />
                  <a
                    href="https://quantum-biotech.my.canva.site/"
                    target="_blank"
                  >
                    <b-button label="Website" type="is-primary" />
                  </a>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import EventForm from '~/components/EventForm.vue'
import Video from '~/components/Video.vue'

export default {
  layout: 'tech',
  data() {
    return {
      isModalActive: false,
      formProps: {
        team: 'test'
      }
    }
  },
  methods: {
    openEventForm(team) {
      this.$buefy.modal.open({
        parent: this,
        component: EventForm,
        props: { team },
        hasModalCard: true,
        trapFocus: true
      })
    },
    openVideo(assetPath) {
      this.$buefy.modal.open({
        parent: this,
        component: Video,
        props: { assetPath },
        trapFocus: true
      })
    }
  }
}
</script>
  