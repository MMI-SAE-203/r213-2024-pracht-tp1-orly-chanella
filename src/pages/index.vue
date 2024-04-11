<!-- eslint-disable vue/multi-word-component-names -->
<script setup lang="ts">
import { ref } from 'vue';
const sectionOpen = ref(1)
//
</script>

<template>
  <h1 class="text-2xl">Bonjour monde !</h1>
  <section>
    <button @click="sectionOpen = 1" class="text-xl" >bouton 1</button>
    <p v-show="sectionOpen === 1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed quam quas eos quisquam deleniti aliquid temporibus! Ea earum quam ipsa libero excepturi blanditiis dolorum architecto omnis, doloremque doloribus culpa! Nisi?</p>
  </section>
  <section>
    <button @click="sectionOpen = 2" class="text-xl">bouton 2</button>
    <p v-show="sectionOpen === 2">Sequi quo reprehenderit repellendus molestias, corporis, magnam optio ad, odio ipsam dolorem facilis? Earum magnam dicta sequi necessitatibus tenetur odit, minima animi nihil! Voluptatibus enim fugiat eos, error facilis eius?</p>
  </section>
  <section>
    <button @click="sectionOpen = 3" class="text-xl">bouton 3</button>
    <p v-show="sectionOpen === 3">Impedit deserunt quaerat ex, perferendis omnis consectetur repellendus non. Quod obcaecati vitae nam quos aliquam voluptatem vero voluptates aut enim ullam? Voluptas perferendis sed similique, pariatur ab quaerat magni eum?</p>
  </section>
</template>
