<template>
  <Tutorial/>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component, Prop } from "nuxt-property-decorator";

@Component({
  components: { },
  head() {
    return {
      title: 'Home'
    };
  },
  name: 'main-page-view'
})

// export default Vue.extend({})
export default class HomePage extends Vue {
  @Prop({ default: true })
  public showSearch: boolean = false;
}
</script>
