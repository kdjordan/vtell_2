<template>
  <div>
      <Hero />
      <Privilege />
      <Advantages />
      <About />
      <Tariffs />
      <Sim />
      <Countries />
  </div>
</template>

<script>
// @ is an alias to /src
import Countries from '@/components/TheCountries.vue'
import Sim from '@/components/TheSim.vue'
import Tariffs from '@/components/TheTariffs.vue'
import About from '@/components/TheAbout.vue'
import Advantages from '@/components/TheAdvantages.vue'
import Privilege from '@/components/ThePrivilege.vue'
import Hero from '@/components/TheHero.vue'

export default {
    name: "home",
    components: {
    Hero,
    Privilege,
    Advantages,
    About,
    Tariffs,
    Sim,
    Countries
    },
    mounted () {
        window.scrollTo(0, 0);
    }
};
</script>
