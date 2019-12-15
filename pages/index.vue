<template>
  <div class="container">
    <div>
      <logo />
      <div class="links">
        <a
          href="https://www.linkedin.com/in/0ndrejcermak/"
          target="_blank"
          class="button linkedin"
        >
          <fa :icon="fab.faLinkedinIn" />
        </a>
        <a
          href="https://github.com/cerondevs"
          target="_blank"
          class="button github"
        >
          <fa :icon="fab.faGithub" />
        </a>
        <a
          href="https://www.instagram.com/oonacermak/"
          target="_blank"
          class="button instagram"
        >
          <fa :icon="fab.faInstagram" />
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { fab } from '@fortawesome/free-brands-svg-icons'
import { fas } from '@fortawesome/free-solid-svg-icons'
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  computed: {
    fab() {
      return fab
    },
    fas() {
      return fas
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.links {
  padding-top: 25px;
  font-size: 22px;
}
.linkedin {
  border: 1px solid #2867b2;
  color: #2867b2;
}

.linkedin:hover {
  color: #fff;
  background-color: #2867b2;
}

.github {
  border: 1px solid #211f1f;
  color: #211f1f;
  margin-left: 5px;
}

.github:hover {
  color: #fff;
  background-color: #211f1f;
}

.instagram {
  border: 1px solid #c13584;
  color: #c13584;
  margin-left: 5px;
}

.instagram:hover {
  color: #fff;
  background-color: #c13584;
}
</style>
