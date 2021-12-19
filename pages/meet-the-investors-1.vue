<template>
  <section class="posts">
    <div class="container">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <div class="columns featured-post is-multiline">
            <div class="column is-12 post">
              <article class="columns featured">
                <div class="column is-10 is-offset-1 featured-content va has-text-centered">
                  <h1 class="title post-title">
                    8 Creative Products
                  </h1>
                  <p class="post-excerpt">
                    ขอเชิญผู้ที่สนใจร่วมต่อยอดธุรกิจนวัตกรรม (Deep Tech Startup) เข้าร่วมกิจกรรม Meet the Investors
                    ภายใต้โครงการ “Organic Tech Accelerator Platform: แพลตฟอร์มเร่งการเติบโตทางธุรกิจด้วยเทคโนโลยีดิจิตอลและนวัตกรรมสร้างสรรค์”
                  </p>
                </div>
              </article>
            </div>
          </div>
          <hr>
          <div class="columns is-multiline">
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/areal.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    Retail
                  </h3>
                  <h1 class="title post-title">
                    AREAL
                  </h1>
                  <p class="post-excerpt">
                    AR-Empowered Marketplace with Real-Time Try on Experience for Jewelry Products. Try on before purchasing. Buy with more confidence in the safety of an online environment.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    @click="openEventForm('AREAL')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/areal.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/dronebox.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    GIS
                  </h3>
                  <h1 class="title post-title">
                    Dronebox
                  </h1>
                  <p class="post-excerpt">
                    A cloud-based image processing platform for drone pilots, designed for simplicity. Within a few clicks of uploading drone images via the browser, Dronebox takes care of generating orthophoto images, digital surfaces and 3D models.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('Dronebox')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/dronebox.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/blackbox.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    MedTech
                  </h3>
                  <h1 class="title post-title">
                    Blackbox
                  </h1>
                  <p class="post-excerpt">
                    Utilizing Ethylene Oxide in the sterilization process with safe manufacturing standards.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('Blackbox')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/blackbox.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/keptfun.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    FinTech
                  </h3>
                  <h1 class="title post-title">
                    Keptfun
                  </h1>
                  <p class="post-excerpt">
                    A fun and easy tool that helps young first jobbers in shaping and building their desirable financial habits for better current and future wealth.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('Keptfun')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/keptfun.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/pantai.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    GIS
                  </h3>
                  <h1 class="title post-title">
                    Pantai RTK
                  </h1>
                  <p class="post-excerpt">
                    High precision RTK GNSS equipment, suitable for land surveying, road construction, river banks surveying and dredging, aerial survey with drones, and civil works.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('Pantai RTK')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/pantai.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/atgait.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    MedTech
                  </h3>
                  <h1 class="title post-title">
                    At-Gait
                  </h1>
                  <p class="post-excerpt">
                    A 3D posture and gait analysis system to support doctors, physical therapists or related health caregivers for screening, follow-up or assessing movement.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('At-Gait')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/atgait.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/destinatech.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    E-Tourism
                  </h3>
                  <h1 class="title post-title">
                    Destinatech
                  </h1>
                  <p class="post-excerpt">
                    AR technology promoting smart and safe tourism, taking tourists to the most important tourist spots, eliminating the problem of getting lost and reducing the risk of infection during pandemic.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('Destinatech')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/destinatech.mp4')"
                  />
                </div>
              </article>
            </div>
            <div class="column post is-6">
              <article class="columns is-multiline">
                <div class="column is-12 post-img">
                  <img src="~/assets/cohort1/biscat.jpg" alt="Featured Image">
                </div>
                <div class="column is-12 featured-content ">
                  <h3 class="heading post-category">
                    Environment
                  </h3>
                  <h1 class="title post-title">
                    Biscat
                  </h1>
                  <p class="post-excerpt">
                    Tailor-made toys for pets using an innovative green process from 100% natural fibers.
                  </p>
                  <br>
                  <b-button
                    label="Meet"
                    type="is-primary"
                    disabled
                    title="Event has ended"
                    @click="openEventForm('Biscat')"
                  />
                  <b-button
                    label="Video"
                    type="is-primary"
                    @click="openVideo('cohort1/biscat.mp4')"
                  />
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
    </div>
    <b-modal
      v-model="isModalActive"
      has-modal-card
      auto-focus
      trap-focus
      can-cancel
      aria-role="dialog"
      aria-label="Example Modal"
      close-button-aria-label="Close"
      aria-modal
    >
      <template #default="props">
        <EventForm v-bind="formProps" @close="props.close" />
      </template>
    </b-modal>
  </section>
</template>

<script>
import EventForm from '~/components/EventForm.vue'
import Video from '~/components/Video.vue'

export default {
  components: {
    EventForm,
    Video
  },
  layout: 'event',
  data () {
    return {
      isModalActive: false,
      formProps: {
        team: 'test'
      }
    }
  },
  methods: {
    openEventForm (team) {
      this.$buefy.modal.open({
        parent: this,
        component: EventForm,
        props: { team },
        hasModalCard: true,
        trapFocus: true
      })
    },
    openVideo (assetPath) {
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