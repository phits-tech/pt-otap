<template>
  <div class="modal-card" style="width: auto;">
    <video controls autoplay>
      <source :src="require(`~/assets/${assetPath}`)" type="video/mp4">
    </video>
  </div>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator'

@Component
export default class EventForm extends Vue {
  @Prop()
  assetPath!: string
}
</script>
