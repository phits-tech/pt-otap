<template>
  <div>
    <section class="section">
      <div class="container">
        <h2 class="subtitle">
          กิจกรรมต่อไป
        </h2>
        <h1 class="title">
          Bootcamp 1: Validation ตรวจสอบความถูกต้อง เหมาะสมของผลิตภัณฑ์
        </h1>
        <div class="level">
          <div class="level-item-left">
            <div class="is-inline-block mr-5 has-text-centered">
              <figure class="image is-96x96 is-inline-block">
                <img class="is-rounded" src="~/assets/images/people/workshop1-speaker1.jpg">
              </figure>
              <div class="has-text-weight-bold has-text-grey">
                รศ อรพิณ สันติธีรากุล
              </div>
            </div>
            <div class="is-inline-block mr-5 has-text-centered">
              <figure class="image is-96x96 is-inline-block">
                <img class="is-rounded" src="~/assets/images/people/workshop1-speaker2.jpg">
              </figure>
              <div class="has-text-weight-bold has-text-grey">
                ดร ศันสนา สิริตาม
              </div>
            </div>
            <div class="is-inline-block has-text-centered">
              <figure class="image is-96x96 is-inline-block">
                <img class="is-rounded" src="~/assets/images/people/workshop1-speaker3.jpg">
              </figure>
              <div class="has-text-weight-bold has-text-grey">
                อ สุพจน์ กุลปรางค์ทอง
              </div>
            </div>
          </div>
          <div class="level-item-right">
            <div class="content is-size-5">
              <b-icon icon="calendar" /> 27-28 กุมภาพันธ์ 2564<br>
              <b-icon icon="pin" /> โรงแรมชินะปุระ
            </div>
          </div>
        </div>

        <hr class="my-6">
        <h2 class="subtitle">
          กิจกรรมที่จะเกิดขึ้น
        </h2>
        <table class="table">
          <thead>
            <tr>
              <th>Date</th>
              <th>Title</th>
              <th>Speakers</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>10 มีนาคม 2564</td>
              <td>การประเมินแผนธุรกิจ และเทคโนโลยี (BMC &amp; TEC)</td>
              <td>ดร ปรเมษฐ์ ชุ่มยิ้ม</td>
            </tr>
            <tr>
              <td>13-14 มีนาคม 2564</td>
              <td>Bootcamp 2: Agile Mindset and Scrum</td>
              <td>คุณ ทวิร พานิชสมบัติ</td>
            </tr>
            <tr>
              <td>3-4 เมษายน 2564</td>
              <td>Bootcamp 3: Design, UX and UI</td>
              <td>คุณ อภิรักษ์ ปนาทกูล</td>
            </tr>
            <tr>
              <td>1-2 พฤษภาคม 2564</td>
              <td>Bootcamp 4: Marketing</td>
              <td>TBC</td>
            </tr>
            <tr>
              <td>14 มิถุนายน 2564</td>
              <td>Bootcamp 5: Investment การตรวจสอบการลงทุน</td>
              <td>TBC</td>
            </tr>
          </tbody>
        </table>

        <hr class="my-6">
        <h2 class="subtitle">
          กิจกรรมที่ผ่านมา
        </h2>

        <h3 class="title">
          OTAP Launch &amp; Orientation
        </h3>
        <div class="level">
          <div class="level-item-left">
            <div class="is-inline-block mr-5 has-text-centered">
              <figure class="image is-96x96 is-inline-block">
                <img class="is-rounded" src="~/assets/images/people/workshop0-speaker1.jpg">
              </figure>
              <div class="has-text-grey">
                <span class="has-text-weight-bold">Kittichai Phiphatbunyarat</span><br>
                <a href="https://apitel.co">Apitel.co</a> / <a href="https://chiangmaiandco.org">Chiangmai&amp;co</a> / ARISTO
              </div>
            </div>
            <div class="is-inline-block mr-5 has-text-centered">
              <figure class="image is-96x96 is-inline-block">
                <img class="is-rounded" src="~/assets/images/people/sukhgij.jpg">
              </figure>
              <div class="has-text-grey">
                <span class="has-text-weight-bold">Sukhgij Ysothonsreekul, Ph.D.</span><br>
                OTAP / Naresuan University
              </div>
            </div>
          </div>
          <div class="level-item-right">
            <div class="content is-size-5">
              <b-icon icon="calendar" /> 20 กุมภาพันธ์ 2564<br>
              <b-icon icon="clock" /> 9:00-14:00<br>
              <b-icon icon="pin" /> สเต็กปีนัง Penang Steak Brasserie<br>
            </div>
          </div>
        </div>
      </div>
    </section>
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
