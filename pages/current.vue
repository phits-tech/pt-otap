<template>
  <div>
    <section class="section">
      <div class="container">
        <h1 class="title">
          Current Schedule
        </h1>
        <h2 class="subtitle">
          Cohort 2
        </h2>
        <div>
          <img src="~/assets/cohort2/schedule.png" style="max-width: 700px;">
        </div>
        <hr>
        <h2 class="title is-4">
          Ignite Proposal (submission 1)
        </h2>
        <div class="content">
        <ul>
          <li>อธิบายผลิตภัณฑ์ และเทคโนโลยี</li>
          <li>อธิบายตลาดกลุ่มเป้าหมายที่คาดการณ์ไว้ พร้อมขนาดตลาด และคู่แข่ง</li>
          <li>จำนวนสมาชิกในทีม ประสบการณ์ ความสามารถของแต่ละคน</li>
          <li>Research and Technology Development Portfolio</li>
          <li>ทรัพย์สินทางปัญญา (ถ้ามี)</li>
        </ul>
        </div>
        <div class="mb-5 level">
          <div class="level-left">
            <a class="button is-link" href="https://docs.google.com/presentation/d/1We5yBVSomkIyMLH8QhFi-KIno72GqQWkD4ucURvBP30/edit?usp=sharing">
              ดาวน์โหลด Template
            </a>
            <a class="button is-primary ml-3" href="https://docs.google.com/forms/d/e/1FAIpQLSfNfSlHLqWP5fgXEavD2gIRgHY_7NyjGLIoMQ9tJaHdmTnxkg/viewform?usp=sf_link">
              ส่งเอกสาร Proposal
            </a>
            <span class="ml-3">
              วันกำหนดส่ง 17 กุมภาพันธ์ เวลา 17:00
            </span>
          </div>
        </div>
        <hr>
        <h2 class="title is-4">
          Ignite Design (submission 2)
        </h2>
        <div class="content">TBC</div>
        <div class="mb-5 level">
          <div class="level-left">
            <a class="button is-link" disabled href="">
              ดาวน์โหลด Template
            </a>
            <a class="button is-primary ml-3" disabled href="">
              ส่งเอกสาร Design
            </a>
            <span class="ml-3">
              วันกำหนดส่ง 3 มีนาคม เวลา 23:59
            </span>
          </div>
        </div>
        <hr>
        <h2 class="title is-4">
          Demo Day
        </h2>
        <div class="content">TBC</div>
        <div class="mb-5 level">
          <div class="level-left">
            <a class="button is-link" disabled href="">
              ดาวน์โหลด Template
            </a>
            <a class="button is-primary ml-3" disabled href="">
              ส่งเอกสาร Pitch Deck
            </a>
            <span class="ml-3">
              วันกำหนดส่ง 30 เมษายน เวลา 23:59
            </span>
          </div>
        </div>
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
