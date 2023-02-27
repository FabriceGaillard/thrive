<script setup>
import Header from "@/components/HeaderComponent.vue";
import Hero from "@/views/HeroView.vue";
import Feeds from "@/components/FeedsComponent.vue";
</script>

<template>
  <Header />
  <main>
    <Hero />
    <div class="container">
      <section style="width: 776px">
        <Feeds />
      </section>
      <!-- 
      <aside>
        <div></div>
        <div>
          <p>Débutant (A2) - Cours 1</p>
          <p>6/7 leçons terminées</p>
        </div>
        <p>
          Parler des sentiments et des relations, parler de ses projets, raconter
          son week-end, prévoir ses vacances
        </p>
        <button>Essayer un autre cours</button>
        <button>Vérifier votre niveau</button>
      </aside> -->
    </div>
  </main>
</template>
