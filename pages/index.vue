<script setup lang="ts">
import Header from '~/shared/components/Header/Header.vue';
import Main from '~/components/Section_1/Main/Main.vue';
import MainSection2 from '~/components/Section_2/Main/MainSection2.vue';
import MainSection3 from '~/components/Section_3/Main/MainSection3.vue';
import MainSection4 from '~/components/Section_4/Main/MainSection4.vue';
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
    <MainSection3/>
    <MainSection4/>
  </div>
</template>

<style scoped></style>