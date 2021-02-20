<template>
  <div>
    <!-- <section class="hero is-medium has-background">
      <img class="hero-background" src="~/assets/images/spacex.jpg">
      <div class="hero-body" />
    </section> -->

    <section class="section">
      <div class="container">
        <h1 class="title">
          Apply
        </h1>
        <p class="has-text-grey is-size-5">
          เปิดรับสมัครรอบต่อไป เดือนกรกฎาคม 2564
        </p>
        <p class="has-text-grey is-size-5 mt-4">
          ติดตามเราได้ที่ <a href="https://www.facebook.com/OTAP-NU-106039058143693">OTAP NU Facebook</a>
        </p>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  &.has-background {
    position: relative;
    overflow: hidden;
  }

  &-background {
    position: absolute;
    object-fit: cover;
    object-position: center center;
    width: 100%;
    height: 100%;

    &.is-transparent {
      opacity: 0.3;
    }
  }
}
</style>
