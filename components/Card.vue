<template>
  <div class="column">
    <div class="card">
      <div class="card-content">
        <div class="content has-text-centered">
          <b-icon
            :icon="icon"
            size="is-large"
            type="is-primary"
          />
          <p class="has-text-grey is-size-4">
            {{ title }}
          </p>
        </div>
      </div>
      <footer class="card-footer">
        <div class="card-footer-item">
          <span>
            <slot />
          </span>
        </div>
      </footer>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator'

@Component
export default class Card extends Vue {
  @Prop()
  title!: string

  @Prop()
  icon!: string
}
</script>
