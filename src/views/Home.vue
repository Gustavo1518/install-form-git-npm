<template>
  <div class="home">
    <h1>FORMULARIO CONACYT</h1>
    <form-conacyt></form-conacyt>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

import { HelloWorldComponent } from "@conacyt/hello-world/src";

@Component({
components: {"form-conacyt": HelloWorldComponent}
  })
export default class Home extends Vue {}
</script>
