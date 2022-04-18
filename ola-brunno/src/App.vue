<script>
import MenuLateral from "@/components/MenuLateral.vue";
import RodapeComp from "@/components/RodapeComp.vue";
import CabecalhoComp from "@/components/CabecalhoComp.vue";
import PrincipalComp from "@/components/PrincipalComp.vue";
export default {
  components: { MenuLateral, RodapeComp, CabecalhoComp, PrincipalComp },
};
</script>
<template>
  <CabecalhoComp></CabecalhoComp>
  <RodapeComp />
  <MenuLateral />
  <PrincipalComp></PrincipalComp>
</template>
