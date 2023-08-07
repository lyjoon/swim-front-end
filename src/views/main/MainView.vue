<template>
  <div>
    <h1>환불해주세요.</h1>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";

@Component
export default class MainView extends Vue {
  protected mounted() {
    console.log("MAIN10000");
  }
}
</script>
