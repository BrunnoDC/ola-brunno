<script>
export default {
  data() {
    return {
      itens: ["Brinquedos", "Louças", "Perfumaria"],
    };
  },
};
</script>
<template>
  <aside id="sidenav">
    <ul>
      <li v-for="(item, i) of itens" :key="i">{{ item }}</li>
    </ul>
  </aside>
</template>
