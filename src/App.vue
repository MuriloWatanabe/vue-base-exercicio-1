<script>
import MenuLateral from "@/components/MenuLateral.vue";
import PrincipalComp from "@/components/PrinciaplComp.vue";
import BlocoPrincipal from "@/components/BlocoPrincipal.vue";
export default {
  components: { MenuLateral, PrincipalComp, BlocoPrincipal },
};
</script>
<template>
  <MenuLateral />
  <PrincipalComp />
  <BlocoPrincipal />
  <header id="header">Cabeçalho</header>
  <main id="content">Principal</main>
  <footer id="footer">Rodapé</footer>
</template>
<style></style>
