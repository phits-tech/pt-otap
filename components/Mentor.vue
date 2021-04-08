<template>
  <div class="card">
    <div class="card-image">
      <figure class="image is-square">
        <img :src="imageSrc" alt="Photo of Apirak">
      </figure>
    </div>
    <div class="card-content">
      <div class="title is-4">
        {{ name }}<br>
        <span class="subtitle is-6" v-if="thaiName">
          ({{ thaiName }})
        </span>
      </div>

      <p class="subtitle is-6">
        {{ topics }}
      </p>
      <p class="content">
        <slot />
        <a v-if="linkedin" :href="'https://www.linkedin.com/in/' + linkedin + '/'"><b-icon
          icon="linkedin"
          style="margin-top: -3px;"
        /></a>
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

  @Prop({ default: '' })
  thaiName!: string

  @Prop()
  imageSrc!: string

  @Prop()
  topics!: string

  @Prop()
  linkedin!: string
}
</script>
