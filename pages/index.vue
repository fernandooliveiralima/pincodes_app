<script setup lang="ts">
import Header from '~/shared/components/Header/Header.vue';
import Main from '~/components/Section_1/Main/Main.vue';
import MainSection2 from '~/components/Section_2/Main/MainSection2.vue';
</script>

<template>
  <div class="w-full bg-primary-blue-300">

    <section>

      <Header />
      <Main />

    </section>

  </div>
  <div>
    <MainSection2 />
  </div>
</template>

<style scoped></style>