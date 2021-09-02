<template>
  <div>
    Login
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { Component, Prop } from "nuxt-property-decorator";

@Component({
  components: { },
  head() {
    return {
      title: 'Login',
    };
  },
  layout: 'anonymous',
  name: 'login-page-view'
})

// export default Vue.extend({})
export default class LoginPageView extends Vue {
}
</script>
