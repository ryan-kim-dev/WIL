<template>
  <div>
    <v-list-item>
      <TooltipedMenuIcon icon="mdi-logout" />
    </v-list-item>
  </div>
</template>

<script>
import TooltipedMenuIcon from '@/components/TooltipedMenuIcon.vue';

export default {
  name: 'Home',
  components: {
    TooltipedMenuIcon,
  },

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="scss" scoped></style>
