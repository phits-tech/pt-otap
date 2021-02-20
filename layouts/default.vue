<template>
  <div>
    <nav class="navbar  is-primary" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-brand">
          <a v-if="$nuxt.$route.name !== 'index'" class="navbar-item is-size-5 has-text-weight-semibold" href="/">
            <img src="~/assets/images/ignite.svg">
            <span>IGNITE</span>
          </a>

          <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
            <span aria-hidden="true" />
            <span aria-hidden="true" />
            <span aria-hidden="true" />
          </a>
        </div>

        <div class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link
              v-for="(item, key) of items"
              :key="key"
              :to="item.to"
              class="navbar-item"
              exact-active-class="is-active"
            >
              {{ item.title }}
            </nuxt-link>

            <div class="navbar-item">
              <div class="buttons">
                <nuxt-link to="apply" class="button is-primary is-inverted is-outlined">
                  <strong>Apply</strong>
                </nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>

    <nuxt />

    <footer class="footer">
      <nav class="level is-mobile">
        <div class="level-item">
          <figure class="image is-48x48 mx-2">
            <img class="is-rounded" src="~/assets/images/logos/otap.png">
          </figure>
          <figure class="image is-48x48 mx-2">
            <a href="https://www.nxpo.or.th/C/"><img class="is-rounded" src="~/assets/images/logos/bpk.png"></a>
          </figure>
          <figure class="image is-48x48 mx-2">
            <a href="https://www.nu.ac.th"><img class="is-rounded" src="~/assets/images/logos/nu.png"></a>
          </figure>
          <figure class="image is-48x48 mx-2">
            <img class="is-rounded" src="~/assets/images/logos/dri.png">
          </figure>
          <figure class="image is-48x48 mx-2">
            <a href="https://www.facebook.com/NU-SciPark-547002178663488"><img class="is-rounded" src="~/assets/images/logos/sci-park.png"></a>
          </figure>
          <figure class="image is-48x48 mx-2">
            <a href="https://www.facebook.com/phits.tech"><img class="is-rounded" src="~/assets/images/logos/phits-tech.png"></a>
          </figure>
        </div>
      </nav>
      <p class="content has-text-centered">
        <strong>IGNITE</strong> ดำเนินการโดย OTAP (Organic Tech Acceleration Platform)<br>
        สนับสนุนโดย <a href="https://www.nxpo.or.th/C/">หน่วยบริหารและจัดการทุนด้านการเพิ่มความสามารถในการแข่งขันของประเทศ (บพข)</a> และ <a href="https://nu.ac.th">มหาวิทยาลัยนเรศวร</a>.
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          title: 'Overview',
          to: { name: 'index' }
        },
        {
          title: 'Workshops',
          to: { name: 'workshops' }
        },
        {
          title: 'Mentors',
          to: { name: 'mentors' }
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
.navbar-brand img {
  width: 3rem;
  height: 3rem;
}
</style>
