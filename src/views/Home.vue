<template>
  <div class="home">
    <div class="notification is-info">
      <Strong>Formulario</Strong>
    </div>
    <form-conacyt></form-conacyt>
  </div>
</template>
<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import { HelloWorldComponent } from "@conacyt/hello-world/src";

@Component({
  components: { "form-conacyt": HelloWorldComponent }
})
export default class Home extends Vue {}
</script>
