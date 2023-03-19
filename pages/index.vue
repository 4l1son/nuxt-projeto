<template>
<main>
  <button>
  <NuxtLink to="/home">Home page</NuxtLink>
</button>
<div>
    <button @click="showModal = true">Ação de Mostrar </button>
    <modal v-if="showModal" @close="showModal = false">
      | Conteudo Mostrado |
    </modal>
    <button @click="showModal = false">Ação de Recolher </button>
   
  </div>
</main>
</template>

<script>
export default {
  data() {
    return {
      showModal: false
    }
  }
}  
</script>
