<template>
  <div>
    <Particles></Particles>
    <div class="text-portion">
      <h2>Who are we?</h2>
      <div>
        Hello, we are Ching Chang and Voovs, we are the developers of Dorpn. We are in high school
        and we love programming in our spare time. This is the first project we made together and we
        really hope to make it simple yet useful.
      </div>
      <h2>Other Sites</h2>
      <div>
        If you are interested in our websites, feel free to check out Ching Chang's website at
        <a href="https://www.chingchang.dev">chingchang.dev</a>, and Voovs' website at
        <a href="https://voovs.github.io/#/">voovs.github.io</a>.
      </div>
    </div>
  </div>
</template>

<script>
import Particles from '@/components/ParticlesJS.vue';

export default {
  name: 'about',
  components: { Particles },
};
</script>

<style scoped>
.text-portion {
  padding: 0px 4vw;
  letter-spacing: 1.5px;
  font-size: 23px;
  color: #e6ecf0;
  word-wrap: break-word;
  margin-bottom: 30px;
}
.text-portion > div {
  text-indent: 55px;
}
a {
  color: #3fb2b8;
}
</style>
