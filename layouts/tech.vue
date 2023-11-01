<template>
  <div>
    <section class="hero is-medium has-background2">
      <div class="hero-head">
        <div class="container">
          <nav class="navbar" role="navigation" aria-label="main navigation">
            <div id="navbarBasicExample" class="navbar-menu">
              <div class="navbar-start">
                <a class="navbar-item is-size-5 has-text-weight-semibold" href="/">
                  <img src="~/assets/images/ignite.svg">
                  <span>IGNITE</span>
                </a>
                <div class="navbar-item is-size-5">
                  presents...
                </div>
              </div>
              <div class="navbar-end">
                <div class="navbar-item">
                  <a href="#">
                    <svg
                      class="svg-inline--fa fa-facebook fa-w-16"
                      data-prefix="fab"
                      data-icon="facebook"
                      role="img"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 512 512"
                      data-fa-i2svg=""
                    ><path fill="currentColor" d="M504 256C504 119 393 8 256 8S8 119 8 256c0 123.78 90.69 226.38 209.25 245V327.69h-63V256h63v-54.64c0-62.15 37-96.48 93.67-96.48 27.14 0 55.52 4.84 55.52 4.84v61h-31.28c-30.8 0-40.41 19.12-40.41 38.73V256h68.78l-11 71.69h-57.78V501C413.31 482.38 504 379.78 504 256z" /></svg><!-- <i class="fab fa-facebook"></i> Font Awesome fontawesome.com -->
                  </a>
                  <a href="#">
                    <svg
                      class="svg-inline--fa fa-twitter fa-w-16"
                      data-prefix="fab"
                      data-icon="twitter"
                      role="img"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 512 512"
                      data-fa-i2svg=""
                    ><path fill="currentColor" d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z" /></svg><!-- <i class="fab fa-twitter"></i> Font Awesome fontawesome.com -->
                  </a>
                  <a href="#">
                    <svg
                      class="svg-inline--fa fa-rss-square fa-w-14"
                      data-prefix="fas"
                      data-icon="rss-square"
                      role="img"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 448 512"
                      data-fa-i2svg=""
                    ><path fill="currentColor" d="M400 32H48C21.49 32 0 53.49 0 80v352c0 26.51 21.49 48 48 48h352c26.51 0 48-21.49 48-48V80c0-26.51-21.49-48-48-48zM112 416c-26.51 0-48-21.49-48-48s21.49-48 48-48 48 21.49 48 48-21.49 48-48 48zm157.533 0h-34.335c-6.011 0-11.051-4.636-11.442-10.634-5.214-80.05-69.243-143.92-149.123-149.123-5.997-.39-10.633-5.431-10.633-11.441v-34.335c0-6.535 5.468-11.777 11.994-11.425 110.546 5.974 198.997 94.536 204.964 204.964.352 6.526-4.89 11.994-11.425 11.994zm103.027 0h-34.334c-6.161 0-11.175-4.882-11.427-11.038-5.598-136.535-115.204-246.161-251.76-251.76C68.882 152.949 64 147.935 64 141.774V107.44c0-6.454 5.338-11.664 11.787-11.432 167.83 6.025 302.21 141.191 308.205 308.205.232 6.449-4.978 11.787-11.432 11.787z" /></svg><!-- <i class="fas fa-rss-square"></i> Font Awesome fontawesome.com -->
                  </a>
                </div>
              </div>
            </div>
          </nav>
        </div>
      </div>
      <div class="hero-body">
        <div class="container has-text-centered">
          <h2 class="title is-1">
          </h2>
          <h3 class="subtitle is-4">
          </h3>
        </div>
      </div>
    </section>
    <nuxt />
    <footer class="footer">
      <nav class="level is-mobile">
        <div class="level-item">
          <figure class="image is-48x48 mx-1">
            <img class="is-rounded" src="~/assets/images/logos/otap.png">
          </figure>
          <figure class="image is-48x48 mx-1">
            <a href="https://www.nxpo.or.th/C/"><img class="is-rounded" src="~/assets/images/logos/bpk.png"></a>
          </figure>
          <figure class="image is-48x48 mx-1">
            <a href="https://www.nu.ac.th"><img class="is-rounded" src="~/assets/images/logos/nu.png"></a>
          </figure>
          <figure class="image is-48x48 mx-1">
            <img class="is-rounded" src="~/assets/images/logos/dri.png">
          </figure>
          <figure class="image is-48x48 mx-1">
            <a href="https://www.facebook.com/NU-SciPark-547002178663488"><img class="is-rounded" src="~/assets/images/logos/sci-park.png"></a>
          </figure>
          <figure class="image is-48x48 mx-1">
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
  },
  head () {
    return {
      bodyAttrs: { class: 'event' }
    }
  }
}
</script>

<style lang="scss">

body.event {
  color: white;
  background: #191b1f;

  a {
    color: #3b7adf;
  }

  a:hover {
    color: #3b7adf;
    text-decoration: underline;
  }

  .button:hover {
    text-decoration: none;
  }

  hr {
    background: #24272c;
  }

  .title,
  .subtitle {
    color: white;
  }

  .navbar {
    background-color: #060606;
  }

  .navbar .navbar-item {
    color: #e4e2ff;
  }

  .navbar .navbar-item.is-active {
    color: #e4e2ff;
    font-weight: 700;
  }

  .navbar a.navbar-item:hover {
    background: transparent;
    color: white;
    text-decoration: none;
  }

  .navbar-brand img {
    width: 3rem;
    height: 3rem;
  }

  .hero {
    background: #060606;

    &.has-background {
      background-image: url('~assets/images/backgrounds/morgan-sessions-YIN4xUBaqnk-unsplash.jpg');
      background-size: cover;
    }

    .navbar {
      background: none;
    }

    .subtitle {
      font-family: 'IBM Plex Serif', serif;
      line-height: 2.5rem;
    }
  }

  .posts {
    min-height: 100vh;
    padding-top: 4rem;
    padding-bottom: 10rem;
  }

  .posts article {
    padding: 1.5rem;
  }

  .posts .post img {
    border-radius: 6px;
  }

  .posts .post .post-category {
    color: #3b7adf;
  }

  .posts .post .post-title {
    font-size: 2.2rem;
  }

  .posts .post .post-excerpt {
    line-height: 1.5rem;
    letter-spacing: 0.03rem;
    font-size: 1.2rem;
    font-family: 'IBM Plex Serif', serif;
    color: #92a3ab;
  }

  .posts .post .featured .featured-image img {
    height: 380px;
  }

  .footer {
    background-color: #060606;

    strong {
      color: #fff;
    }
  }
}

</style>

  
