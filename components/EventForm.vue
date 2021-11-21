<template>
  <div class="modal-card" style="width: auto;">
    <header class="modal-card-head">
      <p class="modal-card-title">
        Request to Meet (3 Dec 2021)
      </p>
      <button
        type="button"
        class="delete"
        @click="$emit('close')"
      />
    </header>
    <section class="modal-card-body">
      <div class="columns is-multiline">
        <div class="column is-half">
          <b-field label="Team / Product">
            <b-input
              v-model="team"
              type="text"
              disabled
              required
            />
          </b-field>
        </div>
        <div class="column is-half">
          <b-field label="Requested Time">
            <b-select
              v-model="requestedTime"
              expanded
              required
            >
              <option value="16:00">
                16:00-16:30
              </option>
              <option value="16:30">
                16:30-17:00
              </option>
              <option value="17:00">
                17:00-17:30
              </option>
              <option value="17:30">
                17:30-18:00
              </option>
            </b-select>
          </b-field>
        </div>
        <div class="column is-half">
          <b-field label="Your Name">
            <b-input
              v-model="name"
              type="text"
              required
            />
          </b-field>
        </div>
        <div class="column is-half">
          <b-field label="Company">
            <b-input
              v-model="company"
              type="text"
            />
          </b-field>
        </div>
        <div class="column is-half">
          <b-field label="Phone number">
            <b-input
              v-model="phone"
              type="text"
              required
            />
          </b-field>
        </div>
        <div class="column is-half">
          <b-field label="Email">
            <b-input
              v-model="email"
              type="text"
            />
          </b-field>
        </div>
      </div>
    </section>
    <footer class="modal-card-foot">
      <b-button
        label="Submit"
        type="is-primary"
        :loading="submitted"
        @click="submit()"
      />
      <span class="is-size-6 ml-2 has-text-grey-light">
        For another day please contact by email: penpondp@nu.ac.th
      </span>
    </footer>
  </div>
</template>

<script lang="ts">
import { Component, Vue, Prop } from 'vue-property-decorator'

@Component
export default class EventForm extends Vue {
  @Prop()
  team!: string

  requestedTime: string = ''
  name: string = ''
  company: string = ''
  phone: string = ''
  email: string = ''

  submitted: boolean = false

  async submit () {
    if (this.requestedTime === '' || this.name === '' || this.phone === '') {
      this.$buefy.toast.open({
        message: 'Required: Requested Time, Your Name and Phone',
        position: 'is-top',
        type: 'is-danger'
      })
      return
    }

    this.submitted = true

    const url = 'https://script.google.com/macros/s/AKfycbwYcHjaTEP1AX88lUZLhrgNaCn79-rORgiI85UIzXGfMTMqFNdMWG0nAgxW2ZElOnUK/exec'
    const body = new FormData()
    body.append('Team', this.team)
    body.append('Requested Time', this.requestedTime)
    body.append('Name', this.name)
    body.append('Company', this.company)
    body.append('Phone', this.phone)
    body.append('Email', this.email)

    try {
      await fetch(url, { method: 'POST', body })
    } catch (error) {
      this.$buefy.toast.open({
        message: 'Something went wrong. Please try again.',
        position: 'is-top',
        type: 'is-danger'
      })
      return
    }

    this.$emit('close')

    this.$buefy.toast.open({
      message: 'Request received! Our team will be in contact shortly to confirm.',
      position: 'is-top',
      type: 'is-success'
    })
  }
}
</script>
