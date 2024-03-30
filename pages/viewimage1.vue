<template>
  <section class="posts">
    <div class="container">
      <div class="columns">
        <div class="column is-10 is-offset-1">
          <div class="columns featured-post is-multiline">
            <div class="column is-12 post center">
              <br />
              <h5 class="title post-title">
                Thailand’xs Taste of Tomorrow: Moving Beyond The Plate
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
                    <img :src="`_nuxt/assets/viewimg1/${index}.jpeg`" :alt="`Image ${index}`" />
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
const path = require("path");

export default {
  layout: "",
  data() {
    return {
      isModalActive: false,
      formProps: {
        team: "test",
      },
    };
  },
  data() {
    return {
      a: 58,
    };
  },
  computed: {
    numberList() {
      return Array.from({ length: this.a }, (_, index) => index + 1);
    },
  },
};
</script>
  