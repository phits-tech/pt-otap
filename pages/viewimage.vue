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
    return {
      a: null
    }
  },
  async asyncData ({ query }) {
    let totalImage = 0
    let imageDir = ''
    let imageLast = ''
    let titles = ''
    const param1 = query.set
    if (param1 && param1 === '1') {
      totalImage = 59
      imageDir = 'viewimg1'
      imageLast = 'jpeg'
      titles = 'Thailand’s Taste of Tomorrow: Moving Beyond The Plate'
    } else if (param1 && param1 === '2'){
      totalImage = 21
      imageDir = 'viewimg2'
      imageLast = 'jpg'
      titles = 'The 1st Thailand Scientific Feng Shui for Modern Entrepreneur'
    } else if (param1 && param1 === '3'){
      totalImage = 19
      imageDir = 'viewimg3'
      imageLast = 'jpg'
      titles = 'Pitching for Innovation One'
    } else if (param1 && param1 === '4'){
      totalImage = 47
      imageDir = 'viewimg4'
      imageLast = 'jpg'
      titles = 'Innovative Local Food for NCDs'
    }
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
