<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import AboutIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import 'vue';
import '@fortawesome/fontawesome-free/css/all.css';
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <AboutIcon />
    </template>
    <template #heading>About</template>

    Nama saya Dody Saputra Simanjorang, saya orang batak. Saya berasal dari Ujung Batu, Rokan Hulu dan saat ini saya berusia 20 tahun dan berkuliah di kampus tercinta UIR, pada saat ini saya berada di semester 4 dan berada di kelas 4A.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Motto Hidup</template>

    Kita harus tetap bernafas walaupun di terpa banyak masalah dan kita harus tetap bersyukur terhadap apapun yang diberikan oleh Tuhan.
    <br />

  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak</template>

       Jika ada yang inigin di tanyakan anda dapat mengubungi saya melalui media sosial dibawah ini

       <div>
    <a href="https://www.instagram.com/dody.cpp/" target="_blank">
      <i class="fab fa-instagram social-icon"></i>
    </a>
    <a href="https://web.facebook.com/?_rdc=1&_rdr" target="_blank">
      <i class="fab fa-facebook social-icon"></i>
    </a>
  </div>

  </WelcomeItem>

</template>

<style scoped>
.social-icon {
  font-size: 24px; /* Sesuaikan ukuran ikon sesuai kebutuhan */
  margin-right: 10px; /* Jarak antara ikon */
}
</style>