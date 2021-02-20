<template>
  <div>
    <section class="hero is-medium is-primary">
      <div class="hero-body">
        <div class="container mb-6">
          <div class="level">
            <div class="level-item-left">
              <p class="title is-1">
                <img src="~/assets/images/ignite.svg" class="brand"> IGNITE
              </p>
              <p class="subtitle">
                Accelerator สำหรับการเริ่มต้นเทคโนโลยีขั้นสูง ที่พิษณุโลก
              </p>
            </div>
            <div class="level-item-right" />
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container my-6">
        <div class="content">
          <h2>IGNITE คืออะไร?</h2>
          <p>
            โปรแกรม 6 เดือนที่จะเร่งพัฒนาผลงานของนักวิจัยร่วมกับผู้ประกอบการนวัตกรรม ให้ก้าวสู่การเป็น  Deep Tech Startups ดำเนินงานภายใต้โครงการ “Organic Tech Accelerator Platform (OTAP) : แพลตฟอร์มเร่งการเติบโตทางธุรกิจด้วยเทคโนโลยีดิจิตอลและนวัตกรรมสร้างสรรค์ให้เติบโตอย่างยั่งยืนในพื้นที่ภาคเหนือตอนล่าง
            ในโปรแกรมจะประกอบด้วย
          </p>
        </div>
        <div class="columns mt-3">
          <card
            title="Workshops"
            icon="school"
          >
            ที่จะเสริมทักษะทั้งในเชิงเทคโนโลยี และมุมมองธุรกิจ
          </card>
          <card
            title="Mentoring"
            icon="account-supervisor"
          >
            การให้คำปรึกษาโดยผู้มีความรู้ความสามารถ มากประสบการณ์
          </card>
          <card
            title="Deep Tech"
            icon="satellite-variant"
          >
            การพบปะ แลกเปลี่ยนความรู้และประสบการณ์
          </card>
          <card
            title="Networking"
            icon="handshake"
          >
            เครือข่ายทางธุรกิจ เทคโนโลยี และนักลงทุน
          </card>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Card from '~/components/Card'

export default {
  name: 'HomePage',

  components: {
    Card
  }
}
</script>

<style lang="scss" scoped>
img.brand {
  width: 3.5rem;
  height: 3.5rem;
}
</style>
