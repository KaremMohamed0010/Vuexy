<template>
  <b-card>
    <!-- about -->
    <div :class="index ? 'mt-2' : ''">
      <h5 class="text-capitalize mb-75">tes</h5>
      <b-card-text> fs </b-card-text>
    </div>
  </b-card>
</template>

<script>
import { BCard, BCardText } from "bootstrap-vue";

export default {
  components: {
    BCard,
    BCardText,
  },
  props: {
    aboutData: {
      type: Object,
      default: () => {},
    },
  },
};
</script>
