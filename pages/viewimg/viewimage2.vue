<template>
  <section class="posts">
    <div class="container">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <div class="columns featured-post is-multiline">
            <div class="column is-12 post center">
              <br />
              <h5 class="title post-title">
                {{ titles }}
              </h5>
            </div>
          </div>
          <hr />
          <div class="columns is-multiline">
            <div
              class="column post is-6"
              v-for="index in numberList"
              :key="index"
            >
              <article class="columns is-multiline">
                <div class="column is-12 featured-content">
                  <div class="column is-12 post-img">
                    <img :src="getImagePath(index)" :alt="`Image ${index}`" />
                  </div>
                  <br />
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

export default {
  layout: '',
  data () {
    const totalImage = 21
    const imageDir = 'viewimg2'
    const imageLast = 'jpg'
    const titles = 'The 1st Thailand Scientific Feng Shui for Modern Entrepreneur'
    return { a: totalImage, imageDir, imageLast, titles }
  },
  computed: {
    numberList () {
      return Array.from({ length: this.a }, (_, index) => index + 1)
    }
  },
  methods: {
    getImagePath (index) {
      return require(`@/assets/${this.imageDir}/${index}.${this.imageLast}`)
    }
  }
}
</script>
