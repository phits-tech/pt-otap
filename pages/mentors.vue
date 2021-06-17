<template>
  <div>
    <section class="section">
      <div class="container">
        <h1 class="title">
          Mentors
        </h1>
        <div class="notification is-link is-light has-text-centered">
          <div class="is-5 mb-3">
            For IGNITE teams, please complete the form to request a mentor.
          </div>
          <div>
            <a class="button is-link" href="https://docs.google.com/forms/d/e/1FAIpQLSe04AbChG3skk1XebBh5rrwv76gSNy53Hi2-Mh83reqOhRT9g/viewform">
              Request A Mentor
            </a>
          </div>
        </div>
        <div class="columns is-multiline">
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/workshop3-speaker1.jpg')"
              name="Apirak Panatkool"
              thai-name="อภิรักษ์ ปนาทกูล"
              topics="UX/UI Design"
              linkedin="apirak"
            >
              ผู้ก่อตั้ง UX Academy และ UX Thailand<br>UX Coach ที่ ODDS
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/pornpat.jpg')"
              name="Pornpat Pimjaroen"
              thai-name="พรภัทร พิมพ์เจริญ"
              topics="UX/UI Design"
              linkedin="pornpat-pimjaroen"
            >
              UX Lead ที่กรุงไทย
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/workshop2-speaker1.jpg')"
              name="Twin Panitsombat"
              thai-name="ทวิร พานิชสมบัติ"
              topics="Agile, Scrum"
            >
              ผู้ก่อตั้ง ODDS<br>Agile Coach.
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/supatida.jpg')"
              name="Supatida Prompayuck"
              thai-name="ศุภธิดา พรหมพยัคฆ์"
              topics="Marketing, Strategy"
              linkedin="supatida"
            >
              ผู้ก่อตั้ง The S Curve Women Techmakers Ambassador ประเทศไทย
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/workshop2-speaker2.jpg')"
              name="Phongsak Ritpitakphong"
              thai-name="พงษ์ศักดิ์ ฤทธิ์พิทักษ์พงศ์"
              topics="Agile, Scrum"
            >
              Agile Coach ที่ ODDS
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/workshop0-speaker1.jpg')"
              name="Kittichai Phiphatbunyarat"
              thai-name="กิตติชัย พิพัฒน์บุณยารัตน์"
              topics="Strategy"
              linkedin="kittichai"
            >
              Apitel.co / Chiangmai&co / ARISTO
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/porramate.jpg')"
              name="Porramate Chumyim"
              thai-name="ปรเมษฐ์ ชุ่มยิ้ม"
              topics="Strategy, Marketing Analytics"
              linkedin="porramate-chumyim-b8257112b"
            >
              ที่ปรึกษาอาวุโส Food Innopolis
              สำนักงานพัฒนาวิทยาศาสตร์และเทคโนโลยีแห่งชาติ (สวทช)
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/wansuree.jpg')"
              name="Wansuree Massagram"
              thai-name="วันสุรีย์ มาศกรัม"
              topics="IoT, Hardware"
              linkedin="wansuree-massagram-43776259"
            >
              ผู้ก่อตั้ง NU Maker Club<br>อาจารย์มหาวิทยาลัยนเรศวร
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/ekkasit.jpg')"
              name="Ekkasit Tiamkaew"
              thai-name="เอกสิทธิ์ เทียมแก้ว"
              topics="Online Marketing, Branding, Content Marketing"
            >
              อาจารย์มหาวิทยาลัยนเรศวร
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/somjintana.jpg')"
              name="Somjintana Korbut"
              thai-name="สมจินตนา กอบุตร"
              topics="Mobile (iOS), Web, Firebase"
              linkedin="somjintana-korbut-7691b4bb"
            >
              ผู้เชี่ยวชาญด้านนักพัฒนาซอฟต์แวร์ของ Google ใน Firebase Mobile Lead ที่ Rainforest Connection
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/charles.jpg')"
              name="Charles Allen"
              topics="Agile, Web, Mobile (Android), Chatbot"
              linkedin="ajahncharles"
            >
              ผู้ชนะ LINEHACK ผู้ร่วมก่อตั้ง Phits Tech โปรแกรมเมอร์หลายภาษา
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/rungsun.jpg')"
              name="Rungsun Promprasith"
              thai-name="รังสรรค์ พรมประสิทธิ์"
              topics="Strategy"
              linkedin="superjoh"
            >
              บริษัท คิวคิว (ประเทศไทย) จำกัด และ บริษัท วาย เอ็ม เอ็ม วาย จำกัด.
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/workshop4-speaker1.jpg')"
              name="Wanitcha Wankhawisun"
              thai-name="วณิชชา วรรคาวิสันต์"
              topics="Online marketing"
            >
              บริษัท พาณิชย์ดิจิทัล จำกัด
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/anuwut.jpg')"
              name="Anuwat Jongyindee"
              thai-name="อนุวัฒน์ จงยินดี"
              topics="Finance, Strategy, Risk management"
            >
              บริษัทพฤกษาโฮลดิ้ง จำกัด (มหาชน)
            </mentor>
          </div>
          <div class="column is-half-tablet is-one-third-desktop is-one-quarter-widescreen">
            <mentor
              :image-src="require('~/assets/images/people/workshop1-speaker3.jpg')"
              name="Supot Kulprangthong"
              thai-name="สุพจน์ กุลปรางค์ทอง"
              topics="Strategy, Marketing"
              linkedin="สุพจน์-กุลปรางค์ทอง-36080779/th"
            >
              ที่ปรึกษาอิสระ
            </mentor>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
