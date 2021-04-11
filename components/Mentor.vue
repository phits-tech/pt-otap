<template>
  <div class="card">
    <div class="card-image">
      <figure class="image is-square">
        <img :src="imageSrc" alt="Photo of Apirak">
      </figure>
    </div>
    <div class="card-content">
      <p class="title is-4">
        <span class="name">
          {{ name }}
        </span>
        <a
          v-if="linkedin"
          :href="'https://www.linkedin.com/in/' + linkedin + '/'"
        >
          <b-icon icon="linkedin" class="linkedin" />
        </a>
      </p>
      <p v-if="thaiName" class="subtitle is-6">
        ({{ thaiName }})
      </p>
      <p class="content">
        <slot />
      </p>
      <p class="tags">
        <span
          v-for="topic in topics.split(', ')"
          :key="topic"
          class="tag is-primary mr-1 mb-1"
        >
          {{ topic }}
        </span>
      </p>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator'

@Component
export default class Card extends Vue {
  @Prop()
  name!: string

  @Prop()
  thaiName!: string

  @Prop()
  imageSrc!: string

  @Prop()
  topics!: string

  @Prop()
  linkedin!: string
}
</script>

<style lang="scss" scoped>
.linkedin {
  margin-left: -30px;
  padding-left: 40px;
}
</style>
